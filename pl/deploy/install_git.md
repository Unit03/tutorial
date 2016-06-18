## Windows

Możesz ściągnąć Gita z [git-scm.com](http://git-scm.com/). Możesz klikać "dalej dalej dalej" na każdym kroku oprócz jednego. W piątym kroku, który nazywa się "Adjusting your PATH environment", wybierz "Run Git and associated Unix tools from the Windows command-line" (opcję na samej górze). Poza tym domyślne ustawienia są w porządku. Upewnij się jeszcze, że w kroku "Configuring the line ending conversions" wybrana jest opcja "Checkout Windows-style, commit Unix-style line endings".

### MacOS

Ściągnij Gita z [git-scm.com](http://git-scm.com/) i postępuj zgodnie z instrukcją.

### Linux

Możliwe, że git jest już zainstalowany domyślnie. Żeby to sprawdzić, uruchom:

    git --version

Jeśli Git powie nam, w jakiej wersji jest zainstalowany - jesteśmy gotowi! Jeśli tak nie jest - konsola wyświetli nam, że nie może znaleźć polecenia `git` - Git powinien być dostępny za pośrednictwem menedżera pakietów, więc spróbuj:

#### Debian lub Ubuntu

    $ sudo apt-get install git

#### Fedora (do wersji 21)

    $ sudo yum install git

#### Fedora (wersje 22+)

    $ sudo dnf install git
