..
    Commands
        ./notes/commands/info.rst
        ./notes/commands/top.rst
        ./notes/commands/pstree.rst
        ./notes/commands/iptables.rst
        ./notes/commands/ntp.rst
        ./notes/commands/sed.rst
        ./notes/commands/dmidecode.rst
        ./notes/commands/lsscsi.rst
        ./notes/commands/xclip.rst
        ./notes/commands/xmodmap.rst
    Coreutils
        ./notes/coreutils/mktemp.rst
        ./notes/coreutils/cut.rst
    Package
        ./notes/package/rpm.rst
        ./notes/package/yum.rst
        ./notes/package/fpm.rst
    Git
        ./notes/git/git_secret.rst
        ./notes/git/blackbox.rst
    Bash
        ./notes/bash/grammar.rst
        ./notes/bash/quoting.rst
        ./notes/bash/parameters.rst
        ./notes/bash/expansion.rst
        ./notes/bash/builtin.rst
    Vim
        ./notes/vim/tricks.rst
        ./notes/vim/options.rst
        ./notes/vim/pattern.rst
        ./notes/vim/editing.rst
        ./notes/vim/window.rst
        ./notes/vim/tabpage.rst
        ./notes/vim/repeat.rst
        ./notes/vim/various.rst
        ./notes/vim/quickfix.rst
        ./notes/vim/map.rst
        ./notes/vim/netrw.rst
    DevOps
        ./notes/devops/puppet38.rst
        ./notes/devops/docker.rst
    Storage
        ./notes/storage/glusterfs.rst
    Database
        ./notes/database/redis.rst
    Hardware
        ./notes/hardware/memory.rst
    Server
        ./notes/server/nginx.rst
        ./notes/server/httpd.rst
        ./notes/server/webdav.rst
        ./notes/server/tigervnc.rst
        ./notes/server/nagios.rst
    Awesome
        ./notes/awesome/redshift.rst
    Misc
        ./notes/miscellaneous/tls_ssl.rst
        ./notes/miscellaneous/linux_network.rst
        ./notes/miscellaneous/linux_process.rst
        ./notes/miscellaneous/programming_language.rst
        ./notes/miscellaneous/operating_system.rst
        ./notes/miscellaneous/desktop_environment.rst
        ./notes/miscellaneous/hardware.rst
        ./notes/miscellaneous/regex.rst
    NS
        ./notes/ns/contentsrv.rst
        ./notes/ns/wordpress.rst
    TODO
         sudo ip route add default via 10.0.0.1 dev eth1 src 10.0.0.14 table e1
         sudo ip route add 127.0.0.0/8 dev lo table e1
         sudo ip rule add from 10.0.0.14 table e1


        ./notes/coreutils/seq.rst
        ./notes/coreutils/csplit.rst
        
        dirname

        fd (https://stackoverflow.com/a/2031100)

        vim:quickfix
        vim:buffer args
        vim:fold
        vim:netrw hide (a key)

        bash: variable @ *

        sudo notifier

        ./notes/storage/nfs.rst

        https://wiki.archlinux.org/index.php/XScreenSaver
        https://wiki.archlinux.org/index.php/Backlight
        https://wiki.archlinux.org/index.php/Display_Power_Management_Signaling
        https://www.jwz.org/xscreensaver/man1.html

        puppet: inherit and include (to get access to a variable that’s set in
        a Puppet class, you have to declare the class (i.e. use the include()
        function or inherit from that class).
        puppet: default resource
        puppet: contain

        bash: $_

Commands/
    `info       </notes/commands/info.html>`_

    `top        </notes/commands/top.html>`_

    `pstree     </notes/commands/pstree.html>`_

    `iptables   </notes/commands/iptables.html>`_

    `ntp        </notes/commands/ntp.html>`_

    `sed        </notes/commands/sed.html>`_

    `dmidecode  </notes/commands/dmidecode.html>`_

    `lsscsi     </notes/commands/lsscsi.html>`_

    `xclip      </notes/commands/xclip.html>`_

    `xmodmap    </notes/commands/xmodmap.html>`_

Coreutils/
    `mktemp     </notes/coreutils/mktemp.html>`_

    `cut        </notes/coreutils/cut.html>`_

Package/
    `RPM        </notes/package/rpm.html>`_

    `yum        <notes/package/yum.html>`_

    `fpm        <notes/package/fpm.html>`_

Bash/
    `grammar    </notes/bash/grammar.html>`_

    `quoting    </notes/bash/quoting.html>`_

    `parameters </notes/bash/parameters.html>`_

    `expansion  </notes/bash/expansion.html>`_

    `builtin    </notes/bash/builtin.html>`_

Vim/
    `tricks     </notes/vim/tricks.html>`_

    `options    </notes/vim/options.html>`_

    `pattern    </notes/vim/pattern.html>`_

    `editing    </notes/vim/editing.html>`_

    `window     </notes/vim/window.html>`_

    `tabage     </notes/vim/tabpage.html>`_

    `repeat     </notes/vim/repeat.html>`_

    `various    </notes/vim/various.html>`_

    `quickfix   </notes/vim/quickfix.html>`_

    `map        </notes/vim/map.html>`_

    `netrw      </notes/vim/netrw.html>`_ 

Git/
    `git secret </notes/git/git_secret.html>`_

    `blackbox   </notes/git/blackbox.html>`_

DevOps/
    `puppet3.8  </notes/devops/puppet38.html>`_

Storage/
    `glusterfs  </notes/storage/glusterfs.html>`_

Database/
    `redis      </notes/database/redis.html>`_

Hardware/
    `memory     </notes/hardware/memory.html>`_

Server/
    `nginx      <notes/server/nginx.html>`_

    `httpd      </notes/server/httpd.html>`_

    `WebDAV     </notes/server/webdav.html>`_

    `TigerVNC   </notes/server/tigervnc.html>`_

    `Nagios     </notes/server/nagios.html>`_

Awesome/
    `redshift   </notes/awesome/redshift.html>`_

Misc/
    `TLS/SSL    </notes/miscellaneous/tls_ssl.html>`_

    `Linux network </notes/miscellaneous/linux_network.html>`_

    `Linux process </notes/miscellaneous/linux_process.html>`_

    `Programming language </notes/miscellaneous/programming_language.html>`_

    `Operating system </notes/miscellaneous/operating_system.html>`_

    `Hardware   </notes/miscellaneous/hardware.html>`_

    `Desktop environment </notes/miscellaneous/desktop_environment.html>`_

    `regex      </notes/miscellaneous/regex.html>`_


HowTo
-----

Q : How to check CentOS version?

A1:
    ::

        $ rpm -q centos-release

A2:
    ::

        $ cat /etc/centos-release

----

Q : How to apply a free doman name?

A : `freenom <https://www.freenom.com/>`_

----

Q : How to find my public ip address?

A1:
    ::

        $ dig +short myip.opendns.com @resolver1.opendns.com

A2:
    ::

        $ dig TXT +short o-o.myaddr.l.google.com @ns1.google.com

A3:
    ::

        $ curl ifconfig.me

R :
    `How to find my public ip address from command line?
    <https://www.cyberciti.biz/faq/how-to-find-my-public-ip-address-from-command-line-on-a-linux/>`_

    `What is 'myip.opendns.com' doing?  <https://unix.stackexchange.com/a/335403>`_

----

Q : How to trim leading and trailing white space from a string in Bash?

A :
    ::

        $ echo " some string  " | xarg
        some string

R :
    `How to trim whitespace from a Bash variable? <https://stackoverflow.com/a/12973694>`_

----

Q : How to get TX/RX ?

A1:
    ::

        $ cat /proc/net/dev

A2:
    ::

        $ ip -s link
        
A3:
    ::

        $ netstat -i

R :
    `How to get TX/RX bytes without ifconfig? <https://serverfault.com/questions/533513/how-to-get-tx-rx-bytes-without-ifconfig>`_

----

Q : How to set default web browser in X11?

A :
    ::

        $ xdg-settings set default-web-browser <firefox.desktop|chromium.desktop>

R:
    `Archwiki: xdg-utils <https://wiki.archlinux.org/index.php/Xdg-utils>`_

