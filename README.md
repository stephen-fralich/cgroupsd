# cgroupsd
This is a Perl program that monitors per user CPU usage via cgroups, then sets a CPU quota up also via cgroups. Thresholds, quotas, etc are configurable in the code.


          Usage: ./cgroupsd [-dfms]

          -d enable debugging output

          -f run in the foreground

          -m monitor only, don't actually enforce quotas

          -s silent, don't notify users that a quota has been enforced
