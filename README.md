# cgroupsd
This is a Perl program that monitors per user CPU usage via cgroups, then when a specified usage threshod is crossed, sets a CPU quota until CPU usage is reduced.


          Usage: ./cgroupsd [-dfms]

                    -d enable debugging output

                    -f run in the foreground

                    -m monitor only, don't actually enforce quotas

                    -s silent, don't notify users that a quota has been enforced
