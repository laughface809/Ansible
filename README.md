# Ansible

- name: Changing perm of "/foo/bar.sh", adding "+x"
  file: dest=/foo/bar.sh mode=a+x
