# SMS_APEX
This is an SF Apex Trigger with class to send a SMS on Contact create. 
It will also post and completed task to the contacts record with the SMS information.

Apex class can be updated to trigger on any SF Object creation. Also can be updated to trigger on Update or Delete of the SF Object as well.

Class is set to opt-in the mobile number of the contact as well, but that piece could be removed if necessary, or a custom field on the object could be verified before opting in the contact.
