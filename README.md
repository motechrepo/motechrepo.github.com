## Motech yum repo

* Install motech repo : 
<code>wget -O /etc/yum.repos.d/motech.repo http://motechrepo.github.com/motech.repo</code>

<code>curl http://motechrepo.github.com/motech.repo>/etc/yum.repos.d/motech.repo</code>
* Verifying repo :
<code>
<b>yum list couchdb motech</b>
Loaded plugins: fastestmirror, refresh-packagekit
Installed Packages
couchdb                   1.2.0-7                                              motech</code>

### Installing

<code> yum install apache-couchdb </code>
