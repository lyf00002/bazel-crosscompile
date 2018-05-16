## local repo, for access to stuff in /usr/local, e.g. cdk

# android
android_sdk_repository(
    name = "androidsdk",
    api_level = 27,
    # Ensure that you have the build_tools_version below installed in the
    # SDK manager as it updates periodically.
    build_tools_version = "27.0.1",
    # Replace with path to Android SDK on your system
    path = "/home/leiyh/Android/Sdk",
)
#
android_ndk_repository(
    name="androidndk",
    path="/home/leiyh/Android/Sdk/ndk-bundle",
    # This needs to be 14 or higher to compile TensorFlow.
    # Please specify API level to >= 21 to build for 64-bit
    # archtectures or the Android NDK will automatically select biggest
    # API level that it supports without notice.
    # Note that the NDK version is not the API level.
    api_level=21)