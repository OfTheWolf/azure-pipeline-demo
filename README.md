# azure-pipeline-demo
Azure pipeline for iOS deployment to AppStore.

# Azure Pipeline Steps
1. Install apple development certificate to keyhcain
2. Install distribution provisioning profile <b>(for manual code signing) </b>
3. Download Authkey p8 file to use in the following steps
4. Archive iOS project
5. Export archive to ipa file
6. Move AuthKey file to ~/.private_keys directory so altool can use it.
7. Upload ipa to AppStore
