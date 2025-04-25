# EmailService
EmailCore - Has the functionality that sends email asynchronously.
EmailSenderConsoleApp - Console Application that sends Email. SMtp Should be set in the appSettings.json
EmailSenderApi - Api will call the method from EmailCore. The SMTP Settings should be set in the appSettings.Json. In order to run it should be set as the start up Project.
EmailServiceWebApp - MVC Application that will call EmailSenderApi which we call the EmailCore - SendEmailAsync method. Make sure the EmailSenderApi is running before sending teh email from teh API.  
