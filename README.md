Needs go >= 1.12

# Upgrade 'Command Line Tools'
https://developer.apple.com/download/more/
open /Library/Developer/CommandLineTools/Packages/macOS_SDK_headers_for_macOS_10.14.pkg

brew upgrade golang
go mod init github.com/olibye/ssh-operator
kubebuilder init --domain positiverobot.com

