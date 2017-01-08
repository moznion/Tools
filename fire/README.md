fire
==

A command to run shell script if the script is existed.

Usage
--

```
$ fire want_to_run.sh
```

Example of using
--

On your `.bashrc` or etc.;

```sh
function cd_with_fire() {
  cd $@ && fire .want_to_run.sh
}
alias cd=cd_with_fire
```

Then directory has been changed, it runs `.want_to_run.sh` if such file is existed.

LICENSE
--

Public domain

