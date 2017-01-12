# marklogic-roxy
Geert's Blog: Capturing - http://grtjn.blogspot.com/

David Cassel: Capturing an App Builder application with Roxy - http://blog.davidcassel.net/2013/08/capturing-an-app-building-application-with-roxy/

Exporting Documents Matching a Query - https://docs.marklogic.com/guide/mlcp/export#id_66898

http://www.vagrantbox.es/
https://www.sitepoint.com/vagrantfile-explained-setting-provisioning-shell/
https://www.vagrantup.com/docs/getting-started/

Vagrantfile: Jenkins - https://gist.github.com/aweijnitz/9628014b766e02f0a4c8

ml new marklogic-roxy --branch=dev --app-type=rest
cd marklogic-roxy/
git init
touch README.md
git add *
git commit -m "first commit"
# Create project on github first
git remote add origin https://github.com/joeg13/marklogic-roxy.git
git push -u origin master

./ml local capture --ml-config

./ml local capture --modules-db=test-modules