pipeline {
agent any {
stages{
stage ('copy-index')
{
steps {  sh 'cp -r index.html /var/www/html
}
stage ('copy-t1')
{
steps {  sh 'cp -r t1 /var/www/html
}
stage ('copy-t2')
{
steps {  sh 'cp -r t2 /var/www/html
}
}
}}
