pkgname=my_packages
pkgver=1.0.0
pkgrel=3
pkgdesc='Meta-package for all official packages installed on the system'
arch=('any')
license=('MIT')
install='scripts.install'
_bootstrap_packages=('base' 'linux' 'linux-firmware' 'lvm2' 'vim' 'intel-ucode' 'networkmanager' 'sudo')
_core_packages=('pipewire' 'pipewire-jack' 'pipewire-pulse' 'wireplumber' 'noto-fonts' 'noto-fonts-extra' 'noto-fonts-cjk' 'noto-fonts-emoji' 'awesome-terminal-fonts' 'powerline-fonts' 'cronie' 'intel-media-driver' 'tlp' 'fprintd' 'lib32-mesa' 'kdepim-runtime' 'bluez' 'bluez-utils' 'bluedevil' 'qt5-imageformats' 'electron19' 'nuspell' 'hunspell-en_us' 'aspell' 'aspell-en' 'ttf-dejavu' 'cantarell-fonts' 'cups' 'system-config-printer' 'foomatic-db' 'foomatic-db-ppds' 'foomatic-db-nonfree' 'foomatic-db-nonfree-ppds' 'gutenprint' 'foomatic-db-gutenprint-ppds' 'ntp' 'base-devel') 
_kde_packages=('plasma-meta' 'plasma-wayland-session' 'kde-accessibility-meta' 'kde-graphics-meta' 'kde-multimedia-meta' 'kde-network-meta' 'kde-pim-meta' 'kde-system-meta' 'kde-utilities-meta' 'phonon-qt5-vlc')
_dev_packages=('git' 'python' 'go' 'gnome-keyring' 'clang' 'ruby' 'nodejs' 'npm' 'elixir' 'rustup' 'jdk-openjdk' 'jdk8-openjdk')
_admin_packages=('hdparm' 'kdiskmark' 'intel-gpu-tools' 'powertop' 'man-db' 'man-pages' 'reflector' 'archey3' 'zsh' 'zsh-completions' 'zsh-theme-powerlevel10k' 'zsh-syntax-highlighting' 'zsh-autosuggestions' 'pkgfile' 'python-gobject' 'fwupd' 's-tui' 'libva-utils' 'cpio' 'rsync' 'android-tools' 'easyeffects' 'parallel' 'lm_sensors' 'debuginfod' 'zellij' 'alsa-utils' 'strace' 'bind' 'sshfs')
_rua_deps=('bubblewrap-suid' 'libseccomp' 'xz' 'shellcheck')
_app_packages=('firefox' 'steam' 'signal-desktop' 'libetebase' 'bitwarden' 'digikam' 'docker' 'docker-compose' 'qemu-full' 'weechat' 'chromium' 'discord' 'libreoffice-still' 'certbot' 'vokoscreen')
depends=("${_bootstrap_packages[@]}" 
	"${_kde_packages[@]}" 
	"${_core_packages[@]}"
	"${_dev_packages[@]}"
	"${_admin_packages[@]}"
	"${_rua_deps[@]}"
	"${_app_packages[@]}"
)
