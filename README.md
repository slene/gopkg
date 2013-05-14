###a sample pkg manager for golang/go

copy `gopkg` to `/usr/local/go/bin` and `chmod u+x gopkg`

make sure your `go` command in your env PATH

sample command:

    gopkg get github.com/astaxie/beego
    gopkg get github.com/astaxie/beego -u
    gopkg get all
    gopkg get all -u
    gopkg build all
    gopkg build all -a
    gopkg install all
    gopkg clean all
    gopkg list
    gopkg arches
