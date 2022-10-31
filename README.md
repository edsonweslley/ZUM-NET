# ZUM-NET
Baseando-se no desenvolvimento do netcat, e utilizando alguns recursos bibliográficos, aqui está uma versão menos robusta do netcat. Com algum nível de aperfeiçoamento vamos causar um verdadeiro ZUM ZUM ZUM no mercado.

**ZUM Net Tool**

To use the tool: `zum.py -t target_host -p port` 
or
`python2.7 zum.py -t target_host -p port`

```
-l --listen                   - listen on [host]:[port] for incoming connections
-e --execution                - execute the given file upon receiving a connections
-c --command                  - initialize a command shell
-u --upload=destination       - upon receiving connection upload a file and write to [destination]
```

## Exemples: 
<p><em>zum.py -t 192.168.0.1 -p 5555 -l -c </p></em>
<p><em>zum.py -t 192.168.0.1 -p 5555 -l -u=c:\target.exe</p></em>
<p><em>zum.py -t 192.168.0.1 -p 5555 -l -e='cat /etc/passwd'</p></em>
<p><em>echo 'ZUMMMMMMM' | ./zum.py -t 192.111.22.33 -p 135</p></em>
