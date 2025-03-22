# Basic HTML Email

Resources and guides for creating basic HTML email templates.

## Resources

| Platform | Resource | Link |
|---|---|---|
| Gmail | How to send HTML email via Gmail | [How to send HTML email via Gmail](https://www.youtube.com/watch?v=MsMSqhMlfao) |
| AppScript | How to send HTML email via AppScript | [How to send HTML email via AppScript](https://codegena.com/send-mail-merge-html-emails-using-google-appscripts/) |

## Code Snippets

```javascript
function myFunction(){
  // html email
  var htmlEmailBody = HtmlService.createTemplateFromFile('html-template-name');

  // email title
  var subject = "sample title..";

  // this must be set or .sendEmail will not work. You can insert your own email address to get a copy of the email or just let it blank. Alternative you can delete bcc and just the emailAddress value to send 1 email only.
  var emailAddress = "";

  // same like emailAddress this must be set aswell. You can just keep it blank and use htmlBody for your html email. Alternative delete htmlBody and use normalBody for plain text email instead.
  var normalBody = "";

  // find any file with this name on your gdrive. If not found email will not be sended..
  var file = DriveApp.getFilesByName('resume_en.pdf');


  if (file.hasNext()) {
    MailApp.sendEmail(emailAddress, subject, normalBody, {
      name: "Dennis Demand",
      attachments: [file.next().getAs(MimeType.PDF)],
      htmlBody: htmlEmailBody.evaluate().getContent(),
      bcc: 'sample1@gmail.com,sample2@web.de'
    });
  }
}
```

## Overview

Basic HTML email templates provide the foundation for creating emails that render consistently across email clients. These templates use simple HTML structures with inline CSS to ensure compatibility with various email providers. This section covers the fundamentals of HTML email development, including setup guides, code snippets, and best practices for creating emails that look good and work well across different platforms. 