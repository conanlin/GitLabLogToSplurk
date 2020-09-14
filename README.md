# GitLabLogToSplurk
Send the application and audit log in GitLab CE server with JSON format to Splurk

## Requirment
- install Filebeat in GitLab CE server
- find your application and audit log in GitLab server
- change the path (default is /var/log/gitlab/gitlab-rails/)

## Note
- Not all detail of log will be sent to Splurk 
