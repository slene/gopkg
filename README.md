###a sample pkg manager for golang/go

copy `gopkg` to `/usr/local/go/bin` and `chmod u+x gopkg`

make sure your `go` command in your env PATH

before run command you have to pre defined pkgurl in file:

    $GOROOT/share/pkgs

like this:

    github.com/astaxie/beego
    github.com/go-sql-driver/mysql
    github.com/russross/blackfriday

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
