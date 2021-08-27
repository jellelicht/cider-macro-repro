Silly repo to demonstrate a weird interaction between cider and a clojure deps.edn project.

Simply open user.clj, run cider-jack-in and cider-macroexpand-all the definterface form. 

Versions:
clojure-tools 1.10.3.943

CIDER 1.1.1 (Plovdiv)

GNU Emacs 27.2 (build 1, x86_64-pc-linux-gnu, GTK+ Version 3.24.24, cairo version 1.16.0)

openjdk version "12" 2019-03-19
OpenJDK Runtime Environment (build 12+0-adhoc..jdk-0276cba45aac)
OpenJDK 64-Bit Server VM (build 12+0-adhoc..jdk-0276cba45aac, mixed mode, sharing)

Cider-jack-in message;
[nREPL] Starting server via /home/auto/.guix-profile/bin/clojure -Sdeps '{:deps {nrepl/nrepl {:mvn/version "0.8.3"} cider/cider-nrepl {:mvn/version "0.26.0"}} :aliases {:cider/nrepl {:main-opts ["-m" "nrepl.cmdline" "--middleware" "[cider.nrepl/cider-middleware]"]}}}' -M:cider/nrepl

The error buffer that results from macroexpanding the definterface form can be found in [cider-error.txt](cider-error.txt).


