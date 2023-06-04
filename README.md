Uppity -- The pastebin client with an attitude

Depends only on Lua and LuaSocket
Optionally it will use LuaRocks 

Usage: uppity [options] [file[s]]

Options:
    -f, --file FILE(s)              list of files to upload
    -s, --service SERVICE           set service to use
    -l, --language LANG             set what language to use
    -e, --expiration EXPIRATION     set when to expire (defaults to 1 day)
    -C, --command COMMAND           run COMMAND and paste the output
    -p, --private                   set private flag if available
    -r, --run                       set run flag (codepad)
    -c, --concat                    concat multiple files into a single upload
                                    default is a separate paste for each file
    -x, --xcut                      read input from clipboard (requires xclip)
    -X, --xpaste                    write url to X primary selection buffer (requires xclip)
    -d, --description DESC          set description of paste
    -n, --nick NICK                 set the name to use for a paste
    -h, --help                      show this help info

    -E, --list-expiration SERVICE   list supported expiration times for a service
    -S, --list-services             list supported services
    -L, --list-languages SERVICE    list supported languages for a service

