# PATH
```bash
echo $PATH | tr ':' '\n'
```

```
/opt/homebrew/opt/java/libexec/openjdk.jdk/Contents/Home/bin
/opt/homebrew/bin
/Users/ajsrivastava/dev/templates/scripts/.venv/bin
/Users/ajsrivastava/.local/bin
/opt/homebrew/opt/java/libexec/openjdk.jdk/Contents/Home/bin
/Users/ajsrivastava/.nvm/versions/node/v24.2.0/bin
/usr/local/bin
/System/Cryptexes/App/usr/bin
/usr/bin
/bin
/usr/sbin
/sbin
/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/local/bin
/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/bin
/var/run/com.apple.security.cryptexd/codex.system/bootstrap/usr/appleinternal/bin
/usr/local/share/dotnet
~/.dotnet/tools
/Applications/iTerm.app/Contents/Resources/utilities
/Users/ajsrivastava/.antigen/bundles/robbyrussell/oh-my-zsh/lib
/Users/ajsrivastava/.antigen/bundles/zsh-users/zsh-syntax-highlighting
```

# Local Binaries
```bash
ls -1 ~/.local/bin ~/bin 2>/dev/null
```

```
/Users/ajsrivastava/.local/bin:
claude
env
env.fish
uv
uvx
```

# Homebrew Packages
```bash
brew list --cask && brew list
```

```
==> Formulae
antigen			gettext			krb5			libtiff			nettle			python@3.13
autoconf		gh			leptonica		libunistring		npth			readline
avro-c			giflib			libarchive		libusb			nspr			snappy
bash			git-filter-repo		libassuan		libx11			nss			sqlite
bat			glib			libb2			libxau			oniguruma		swig
ca-certificates		gmp			libevent		libxcb			openjdk			terminal-notifier
cairo			gnupg			libgcrypt		libxdmcp		openjpeg		terraform
coreutils		gnutls			libgit2			libxext			openssl@3		tesseract
databricks		go			libgpg-error		libxrender		p11-kit			unbound
direnv			gpgme			libidn2			little-cms2		pango			webp
fd			graphite2		libksba			lolcat			pcre2			websocat
figlet			harfbuzz		libnghttp2		lz4			pinentry		xorgproto
fontconfig		icu4c@77		libpng			lzlib			pixman			xz
freetype		jansson			librdkafka		lzo			pkgconf			yajl
fribidi			jpeg-turbo		libserdes		m4			poppler			zoxide
fx			kafka			libssh2			mpdecimal		postgresql@14		zstd
fzf			kcat			libtasn1		ncurses			pyenv

==> Casks
1password-cli	dotnet-sdk	libreoffice	ngrok
```

# Install
1. Rectangle
2. LinearMouse
3. 1Password
4. Ollama
5. SparkMail
6. iTerm
7. Visual Studio Code
8. Docker
9. Postman
10. AWS CLI
11. Claude Code
12. Jetbrains IDEs

# GLOBAL PACKAGES
```
pip3 list
Package Version
------- -------
gpg     1.24.3
pip     25.1.1
wheel   0.45.1
```

```
 npm list -g --depth=0
/Users/ajsrivastava/.nvm/versions/node/v24.2.0/lib
├── @angular/cli@20.1.3
├── @nestjs/cli@11.0.10
├── corepack@0.33.0
├── nodemon@3.1.10
└── npm@11.3.0