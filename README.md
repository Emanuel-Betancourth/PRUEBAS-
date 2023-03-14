C:\CMDER\ejercicios                                                                                                                                                     
λ cd                                                                                                                                                                    
C:\CMDER\ejercicios                                                                                                                                                     
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ gitconfig                                                                                                                                                             
"gitconfig" no se reconoce como un comando interno o externo,                                                                                                           
programa o archivo por lotes ejecutable.                                                                                                                                
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ git config                                                                                                                                                            
usage: git config [<options>]                                                                                                                                           
                                                                                                                                                                        
Config file location                                                                                                                                                    
    --global              use global config file                                                                                                                        
    --system              use system config file                                                                                                                        
    --local               use repository config file                                                                                                                    
    --worktree            use per-worktree config file                                                                                                                  
    -f, --file <file>     use given config file                                                                                                                         
    --blob <blob-id>      read config from given blob object                                                                                                            
                                                                                                                                                                        
Action                                                                                                                                                                  
    --get                 get value: name [value-pattern]                                                                                                               
    --get-all             get all values: key [value-pattern]                                                                                                           
    --get-regexp          get values for regexp: name-regex [value-pattern]                                                                                             
    --get-urlmatch        get value specific for the URL: section[.var] URL                                                                                             
    --replace-all         replace all matching variables: name value [value-pattern]                                                                                    
    --add                 add a new variable: name value                                                                                                                
    --unset               remove a variable: name [value-pattern]                                                                                                       
    --unset-all           remove all matches: name [value-pattern]                                                                                                      
    --rename-section      rename section: old-name new-name                                                                                                             
    --remove-section      remove a section: name                                                                                                                        
    -l, --list            list all                                                                                                                                      
    --fixed-value         use string equality when comparing values to 'value-pattern'                                                                                  
    -e, --edit            open an editor                                                                                                                                
    --get-color           find the color configured: slot [default]                                                                                                     
    --get-colorbool       find the color setting: slot [stdout-is-tty]                                                                                                  
                                                                                                                                                                        
Type                                                                                                                                                                    
    -t, --type <type>     value is given this type                                                                                                                      
    --bool                value is "true" or "false"                                                                                                                    
    --int                 value is decimal number                                                                                                                       
    --bool-or-int         value is --bool or --int                                                                                                                      
    --bool-or-str         value is --bool or string                                                                                                                     
    --path                value is a path (file or directory name)                                                                                                      
    --expiry-date         value is an expiry date                                                                                                                       
                                                                                                                                                                        
Other                                                                                                                                                                   
    -z, --null            terminate values with NUL byte                                                                                                                
    --name-only           show variable names only                                                                                                                      
    --includes            respect include directives on lookup                                                                                                          
    --show-origin         show origin of config (file, standard input, blob, command line)                                                                              
    --show-scope          show scope of config (worktree, local, global, system, command)                                                                               
    --default <value>     with --get, use default value when missing entry                                                                                              
                                                                                                                                                                        
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ global                                                                                                                                                                
"global" no se reconoce como un comando interno o externo,                                                                                                              
programa o archivo por lotes ejecutable.                                                                                                                                
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ --global                                                                                                                                                              
"--global" no se reconoce como un comando interno o externo,                                                                                                            
programa o archivo por lotes ejecutable.                                                                                                                                
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ --global                                                                                                                                                              
"--global" no se reconoce como un comando interno o externo,                                                                                                            
programa o archivo por lotes ejecutable.                                                                                                                                
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ $ git config --global user.name "Emmanuel                                                                                                                             
"$" no se reconoce como un comando interno o externo,                                                                                                                   
programa o archivo por lotes ejecutable.                                                                                                                                
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ git config --global user.name "Emmanuel                                                                                                                               
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ --global                                                                                                                                                              
"--global" no se reconoce como un comando interno o externo,                                                                                                            
programa o archivo por lotes ejecutable.                                                                                                                                
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ --global emmanuel                                                                                                                                                     
"--global" no se reconoce como un comando interno o externo,                                                                                                            
programa o archivo por lotes ejecutable.                                                                                                                                
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ --global Emmanuel                                                                                                                                                     
"--global" no se reconoce como un comando interno o externo,                                                                                                            
programa o archivo por lotes ejecutable.                                                                                                                                
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ git config list                                                                                                                                                       
error: key does not contain a section: list                                                                                                                             
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ git config --list                                                                                                                                                     
core.symlinks=false                                                                                                                                                     
core.autocrlf=true                                                                                                                                                      
core.fscache=true                                                                                                                                                       
color.interactive=true                                                                                                                                                  
color.ui=auto                                                                                                                                                           
help.format=html                                                                                                                                                        
diff.astextplain.textconv=astextplain                                                                                                                                   
rebase.autosquash=true                                                                                                                                                  
filter.lfs.clean=git-lfs clean -- %f                                                                                                                                    
filter.lfs.smudge=git-lfs smudge -- %f                                                                                                                                  
filter.lfs.process=git-lfs filter-process                                                                                                                               
filter.lfs.required=true                                                                                                                                                
credential.helper=helper-selector                                                                                                                                       
user.name=Emmanuel                                                                                                                                                      
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ git config --global user.email emanuelbetancur404gmail.com                                                                                                            
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ git config --list                                                                                                                                                     
core.symlinks=false                                                                                                                                                     
core.autocrlf=true                                                                                                                                                      
core.fscache=true                                                                                                                                                       
color.interactive=true                                                                                                                                                  
color.ui=auto                                                                                                                                                           
help.format=html                                                                                                                                                        
diff.astextplain.textconv=astextplain                                                                                                                                   
rebase.autosquash=true                                                                                                                                                  
filter.lfs.clean=git-lfs clean -- %f                                                                                                                                    
filter.lfs.smudge=git-lfs smudge -- %f                                                                                                                                  
filter.lfs.process=git-lfs filter-process                                                                                                                               
filter.lfs.required=true                                                                                                                                                
credential.helper=helper-selector                                                                                                                                       
user.name=Emmanuel                                                                                                                                                      
user.email=emanuelbetancur404gmail.com                                                                                                                                  
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ cd C:\CMDER\ejercicios git init                                                                                                                                       
El sistema no puede encontrar la ruta especificada.                                                                                                                     
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ C:\CMDER\ejercicios git init                                                                                                                                          
"C:\CMDER\ejercicios" no se reconoce como un comando interno o externo,                                                                                                 
programa o archivo por lotes ejecutable.                                                                                                                                
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ cd C:\CMDER\ejercicios                                                                                                                                                
                                                                                                                                                                        
C:\CMDER\ejercicios                                                                                                                                                     
λ git init                                                                                                                                                              
hint: Using 'master' as the name for the initial branch. This default branch name                                                                                       
hint: is subject to change. To configure the initial branch name to use in all                                                                                          
hint: of your new repositories, which will suppress this warning, call:                                                                                                 
hint:                                                                                                                                                                   
hint:   git config --global init.defaultBranch <name>                                                                                                                   
hint:                                                                                                                                                                   
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and                                                                                                 
hint: 'development'. The just-created branch can be renamed via this command:                                                                                           
hint:                                                                                                                                                                   
hint:   git branch -m <name>                                                                                                                                            
Initialized empty Git repository in C:/CMDER/ejercicios/.git/                                                                                                           
                                                                                                                                                                        
C:\CMDER\ejercicios (master)                                                                                                                                            
λ git add                                                                                                                                                               
Nothing specified, nothing added.                                                                                                                                       
hint: Maybe you wanted to say 'git add .'?                                                                                                                              
hint: Turn this message off by running                                                                                                                                  
hint: "git config advice.addEmptyPathspec false"                                                                                                                        
                                                                                                                                                                        
C:\CMDER\ejercicios (master)                                                                                                                                            
λ git commit -m "version inicial"                                                                                                                                       
On branch master                                                                                                                                                        
                                                                                                                                                                        
Initial commit                                                                                                                                                          
                                                                                                                                                                        
Untracked files:                                                                                                                                                        
  (use "git add <file>..." to include in what will be committed)                                                                                                        
        ejercicio1/                                                                                                                                                     
                                                                                                                                                                        
nothing added to commit but untracked files present (use "git add" to track)                                                                                            
                                                                                                                                                                        
C:\CMDER\ejercicios (master)                                                                                                                                            
λ git add ejercicio1/                                                                                                                                                   
                                                                                                                                                                        
C:\CMDER\ejercicios (master)                                                                                                                                            
λ git commit -m "version inicial"                                                                                                                                       
[master (root-commit) 0568df5] version inicial                                                                                                                          
 1 file changed, 0 insertions(+), 0 deletions(-)                                                                                                                        
 create mode 100644 ejercicio1/README.md                                                                                                                                
                                                                                                                                                                        
C:\CMDER\ejercicios (master)                                                                                                                                            
λ                                                                                                                                                                       