pipeline {
agent any {
stages{
stage ('copy-t1')
{
steps {  sh 'cp -r t1 /var/www/html
}
stage ('copy-t2')
{
steps {  sh 'cp -r t2 /var/www/html
}
stage ('copy-t3')
{
steps {  sh 'cp -r t3 /var/www/html
}
stage ('restart-apache')
{stage{
steps { sh 'service start httpd'
}
}
}}
