# HOW TO COMPILE
- 1.) `cd submodules && git submodule update --init --recursive`
- 2.) `cd tensorflow`
- 3.) `git checkout <target_revision>`
- 4.) `cd ../ bash update-downloads.sh`
- 5.) `bash ./gtest_installer` installs gtest if you do not have it in your usr/includes
- 6.) `cargo build`
- 7.) Bindings are output to the target directory
