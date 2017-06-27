Groovy Config Writer
-------------------------------
This Library is a first attempt, at making a config writer for the groovy format used, by the config
slurper. I don't make any claims that this covers all edge cases, in fact there are a few hacks to
make this work with a sample from Grails application.yml. If you come across edge cases that don't
work be sure to raise an issue on github:
https://github.com/virtualdogbert/GroovyConfigWriter/issues

I wrote this to be used in a script to provide a conversion from yml to groovy, which I though there
should be, because I find the groovy format to be more flexible, and readable, then yml. I found it
Strange when Graeme Rocher said:
"But to answer the question more concretely we wanted a format that is machine writeable as well as readable﻿"
- https://www.youtube.com/watch?v=aro3_RZqgtU

Surely since there is a Config Slurper, there has to be a config writer right? Well I was wrong, and
that was another big reason, why I wrote this library.


For documentation see the github page:
[documentation](https://virtualdogbert.github.io/GroovyConfigWriter/)