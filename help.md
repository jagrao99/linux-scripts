
 install the dependency packages
$ yum deplist bind | awk '/provider:/ {print $2}' | sort -u | xargs yum -y install
