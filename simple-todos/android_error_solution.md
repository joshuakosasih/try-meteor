In tutorial step 6. Running on Mobile you will found some error when walking through http://guide.meteor.com/mobile.html#installing-prerequisites

Its likely caused by deprecated android tools being used by Meteor

Meteor called $ANDROID_HOME/tools/android for installing the SDK and creating AVD

But $ANDROID_HOME/tools/android was deprecated and changed to $ANDROID_HOME/tools/bin/sdkmanager and $ANDROID_HOME/tools/bin/avdmanager

So you need to install the SDK manually using sdkmanager and create an AVD manually using avdmanager

The $ANDROID_HOME/tools/emulator was also deprecated and changed to $ANDROID_HOME/emulator/emulator

So manage your environment paths well to ensure a smooth tutorial
