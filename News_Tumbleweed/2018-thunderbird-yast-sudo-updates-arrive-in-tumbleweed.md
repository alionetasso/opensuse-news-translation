Les mises à jour de Thunderbird, YaST et Sudo arrivent dans Tumbleweed

*29 novembre 2018 par Douglas DeMaio*

Trois instantanés [openSUSE](https://www.opensuse.org/) [Tumbleweed](https://en.opensuse.org/Portal:Tumbleweed) ont été publiés depuis le dernier compte-rendu.

Les trois instantanés [Tumbleweed](https://en.opensuse.org/Portal:Tumbleweed) de cette semaine ont apporté un noyau [Linux Kernel](https://www.kernel.org/) plus récent, des mises à jour de plusieurs paquets [rubygem](https://rubygems.org/) et des améliorations pour une bibliothèque annexe pour [Xfce](https://www.xfce.org/).

L'instantané [20181126](https://lists.opensuse.org/opensuse-factory/2018-11/msg00290.html) a fourni le noyau [Linux Kernel](https://www.kernel.org/) 4.19.4, qui corrigeait la gestion des VLAN et une fuite de mémoire avec le *secure boot* avec [Nouveau](https://nouveau.freedesktop.org/wiki/).

Le paquet [YaST](https://en.wikipedia.org/wiki/YaST) (Yet another Setup Tool) a mis à jour *yast2-fonts* 4.0.2 avec des polices qui modifient globalement les polices du bureau et plusieurs traductions ont également été mises à jour avec le paquet *yast2-trans*.

La bibliothèque pour l’environnement de bureau [Xfce desktop environment](https://www.xfce.org/), *[exo](http://www.linuxfromscratch.org/blfs/view/cvs/xfce/exo.html)* est mise à jour vers la version 0.12.3; cela améliore l'espacement et l'alignement de la disposition et masque les lanceurs *exo* de [GNOME Software](https://wiki.gnome.org/Apps/Software).

Le paquet de l'environment de développement intégré [Kdevelop5 5.3.0](https://www.kdevelop.org/news/kdevelop-530-released), apporte une prise en charge améliorée du langage pour *[php](http://www.php.net/)*, *[python](https://www.python.org/)* et *[c++](https://en.wikipedia.org/wiki/C%2B%2B)* et propose également un nouveau plugin analyseur *[clazy](https://github.com/KDE/clazy)*.

Plusieurs autres bibliothèques ont été mises à jour, notamment *[libjansson](http://www.digip.org/jansson/)* 2.11, *, [libsemanage](https://github.com/SELinuxProject/selinux/tree/master/libsemanage)* 2.8, *[libsepol](https://github.com/SELinuxProject/selinux/tree/master/libsepol)* 2.8, *[libzypp](https://github.com/openSUSE/libzypp)* 17.9.0 et plus. Plusieurs paquets *[rubygem](https://rubygems.org/)* ont aussi été mis à jour dans la capture instantanée et rubygem-bundler 1.17.1 comportait une quantité importante d'ajouts et d'améliorations, notamment une option de configuration permettant de désactiver les avertissements de plate-forme.
Le paquet [mailutils](https://mailutils.org/) 3.5 pour la gestion du courrier électronique a corrigé un bogue dans le codeur [base64 encoder](https://www.base64encode.org/).
Le générateur de parseur [bison 3.2.2](http://savannah.gnu.org/forum/forum.php?forum_id=9274) 3.2.2 a apporté d’énormes améliorations au squelette déterministe C ++, lalr1.cc et à la bibliothèque de manipulation des images TIFF, [tiff 4.0.10](http://www.simplesystems.org/libtiff/) 4.0.10, avec l’ajout de quelques correctifs qui traitent 10 patches de vulnérabilités [Common Vulnerabilities and Exposures](https://en.wikipedia.org/wiki/Common_Vulnerabilities_and_Exposures) (Common Vulnerabilities and Exposures) qui ont pu être supprimés.

Huit paquets ont été mis à jour dans l'instantané [20181122](https://lists.opensuse.org/opensuse-factory/2018-11/msg00277.html).
Trois d'entre eux étaient des paquets associés à YaST, tels que yast2-ntp-client 4.1.6, qui alignait un bouton «Synchroniser maintenant» et une zone «Adresse du serveur NTP», qui ne cassaient pas le correctif précédent et ne masquaient pas la case à cocher manuelle dans [TextMode](https://en.wikipedia.org/wiki/Text_mode).
La quatrième version candidate de l'implementation libre  du protocole [RDP](https://en.wikipedia.org/wiki/Remote_Desktop_Protocol) (Remote Desktop Protocol), *[freerdp](http://www.freerdp.com/)* 2.0.0, ajoutait la prise en charge permettant de définir le niveau de sécurité TLS ([Transport Layer Security](https://en.wikipedia.org/wiki/Transport_Layer_Security)) pour *[openssl 1.1.0](https://www.openssl.org/news/openssl-1.1.0-notes.html)* 1.1.0, ainsi que la prise en charge de la carte à puce pour les filtres de sous-chaîne. [sudo 1.8.26](https://www.sudo.ws/stable.html#1.8.26) prend maintenant en charge les variables d'environnement LOGNAME et USER (ainsi que la variable LOGIN sous AIX) comme une seule unité avec la mise à jour vers sudo 1.8.26, qui a également ajouté la prise en charge du paramètre OpenLDAP TLS_REQCERT dans le fichier [ldap.conf](https://www.openldap.org/software/man.cgi?query=ldap.conf). Le paquet [xapian-core 1.4.9](https://xapian.org/docs/xapian-core-1.4.9/NEWS) a corrigé un bogue pour gérer efficacement l’insertion d’un lot de positions supplémentaires par ordre croissant, ce qui pouvait entraîner des positions manquantes et la corruption des données de position codées.

L'instantané Tumbleweed [20181120](https://lists.opensuse.org/opensuse-factory/2018-11/msg00271.html) a apporté [Mozilla Thunderbird 60.3.1](https://www.thunderbird.net/notes/) et cette version corrige la suppression des cookies qui ne fonctionnait plus depuis la version 52 de [Thunderbird](https://support.mozilla.org/en-US/kb/new-thunderbird-52). [GNU Compiler Collection 8](https://gcc.gnu.org/gcc-8/changes.html) a mis à jour la branche principale et supprimé un correctif. Le [gobject-introspection 1.58.1](http://www.linuxfromscratch.org/blfs/view/cvs/general/gobject-introspection.html) a supprimé un correctif pour *warnlib* et a ajouté de nouveau le fichier `/usr/bin/env` à *python-cmd*.
La seule mise à jour majeure de cette semaine concerne la mise à jour du paquet d'iso-codes de la version 3.79 à la version 4.1, qui a mis à jour les langues d'Afrique du Sud et les traductions en italien et en estonien. Les paquets de vérification orthographique [gtkspell3](https://gtkspell.sourceforge.io/) 3.0.10 et [hunspell](https://en.wikipedia.org/wiki/Hunspell) 1.7.0 ont reçu des mises à jour mineures. Le kit de développement logiciel (Plug-and-Play) Universal Plug and Play ([libupnp](http://pupnp.sourceforge.net/) 1.8.4), fourni des correctifs permettant de communiquer correctement avec certains téléviseurs et ainsi que des correctifs du compilateur. [Skopeo](https://github.com/containers/skopeo/blob/master/README.md) 0.1.32, utilitaire en ligne de commande, a mis à jour des bibliothèques et mis à jour l’emplacement du projet depuis "*projectatomic*" à "*conteneurs*". Le paquet du système de fichiers [xfsprogs](http://xfs.org/index.php/Getting_the_latest_source_code) 4.19.0 a supprimé le support de [retpoline](https://stackoverflow.com/questions/48089426/what-is-a-retpoline-and-how-does-it-work) et apporté de nombreuses modifications de la libxfs 4.19 fusionnées depuis le noyau.

D'après [l'analyseur de snapshots Tumbleweed](http://review.tumbleweed.boombatower.com/), l'instantané [20181120](https://lists.opensuse.org/opensuse-factory/2018-11/msg00271.html) a été gratifié d'un indice modérément stable de 83, l'instantané [20181122](https://lists.opensuse.org/opensuse-factory/2018-11/msg00277.html) a d'une note de 91 et l'instantané [20181126](https://lists.opensuse.org/opensuse-factory/2018-11/msg00290.html) d'un score de 88.