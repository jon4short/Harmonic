# Harmonic Music

A cross-platform music streaming app made with Flutter (Android, Windows, Linux) - Enhanced Fork of Harmony Music

## 🎵 About This Fork

This is a significantly enhanced fork of the original [Harmony Music](https://github.com/anandnet/Harmony-Music) project with numerous improvements, bug fixes, and new features. While maintaining the core functionality of the original project, this fork focuses on stability, performance, and user experience enhancements.

## 🔄 Fork Improvements

### 🛠️ Technical Improvements
- **Enhanced Equalizer System**: Built-in Media Kit equalizer with 10-band frequency control
- **Proper Logging Framework**: Replaced all print statements with production-ready logging
- **Code Quality**: Fixed 25+ code analysis issues and warnings
- **Package Name Update**: Updated from `com.anandnet.harmonymusic` to `com.jon4short.harmonic`
- **JNI Bindings Fix**: Corrected package name mismatches in Android Kotlin bindings
- **Permission Fixes**: Added necessary Android permissions for audio effects
- **Cross-Platform Audio Backend**: Media Kit integration for consistent audio experience across platforms
- **Modern Dependencies**: Updated to latest versions of key packages

### 🎚️ Audio Features
- **Built-in Equalizer**: 10-band equalizer with ±15dB range and 7 preset profiles
- **Custom Presets**: Save and load custom equalizer configurations
- **Media Kit Integration**: Direct MPV audio filter support (when available)
- **System Equalizer Fallback**: Automatic fallback to Android system equalizer
- **Nothing Device Support**: Special handling for Nothing phones/buds audio processing
- **Advanced Audio Processing**: Pitch control and audio enhancement features
- **Loudness Normalization**: Automatic volume leveling across tracks
- **Skip Silence**: Automatically skip silent portions in tracks
- **Pitch Control**: Adjustable pitch from -6 to +6 semitones with visual feedback

### 📱 UI/UX Enhancements
- **Modern Material Design 3**: Updated UI with Material Design 3 components
- **Equalizer Screen**: Dedicated equalizer interface with vertical sliders
- **Preset Chips**: Easy selection of audio profiles
- **Real-time Feedback**: Visual indicators for active equalizer settings
- **Improved Navigation**: Enhanced sidebar and tab navigation
- **Dynamic Themes**: System-aware dark/light mode with custom color schemes
- **Pitch Control Interface**: Intuitive slider and buttons for pitch adjustment

### 🎵 Music Intelligence Features
- **Key Detection**: Automatic musical key detection using AudioFlux library
- **Musical Analysis**: Advanced audio analysis capabilities
- **Smart Playlists**: Algorithmically generated music recommendations

### 🧪 Testing & Quality
- **Comprehensive Test Suite**: 12 test cases covering equalizer functionality
- **AudioFlux Testing**: Key detection service testing
- **Widget Tests**: Basic UI component verification
- **Production Logging**: Proper error handling and logging throughout

### 🗑️ Cleanup & Optimization
- **Removed Unnecessary Files**: Deleted 17+ temporary scripts and test files
- **Unused Import Cleanup**: Removed 9+ unused import warnings
- **Code Modernization**: Updated deprecated methods and practices
- **Performance Improvements**: Optimized audio streaming and caching

## 📋 Major Changes from Original

### Core Functionality
1. **Equalizer Redesign**: Completely rebuilt equalizer system with Media Kit support
2. **Audio Processing**: Enhanced audio filter implementation using MPV superequalizer
3. **Device Compatibility**: Special handling for Nothing ecosystem devices
4. **Error Handling**: Robust error handling with proper logging instead of print statements
5. **Cross-Platform Consistency**: Unified audio backend using Media Kit for all platforms
6. **Pitch Control**: Added pitch shifting capability from -6 to +6 semitones

### Code Structure
1. **New Models**: `EqualizerBand`, `EqualizerPreset`, `EqualizerConfig` data models
2. **Services**: `MediaKitEqualizer` service for audio processing
3. **UI Components**: Dedicated equalizer screen with Material Design 3
4. **Testing**: Comprehensive test suite for new functionality
5. **Audio Intelligence**: Key detection service with AudioFlux integration
6. **Pitch Control**: Player controller enhancements for pitch management

### Android Integration
1. **Package Name**: Changed from `com.anandnet.harmonymusic` to `com.jon4short.harmonic`
2. **Permissions**: Added `MODIFY_AUDIO_SETTINGS` and `RECORD_AUDIO` for equalizer
3. **JNI Bindings**: Fixed package name mismatches in Kotlin bindings
4. **Manifest Updates**: Updated AndroidManifest.xml with proper permissions

## 🎯 Features

All original Harmony Music features plus these enhancements:

### 🔊 Audio Features
* ✅ Enhanced Equalizer with 10-band control (±15dB range)
* ✅ 7 Built-in Presets (Flat, Rock, Pop, Jazz, Classical, Bass Boost, Vocal Boost)
* ✅ Custom preset saving/loading
* ✅ System equalizer fallback for Android
* ✅ Nothing device audio processing compatibility
* ✅ Pitch control and audio enhancement (-6 to +6 semitones)
* ✅ Loudness normalization
* ✅ Skip silence functionality
* ✅ Advanced audio filtering via MPV

### 🎵 Music Intelligence
* ✅ Automatic musical key detection (using AudioFlux)
* ✅ Smart music analysis and recommendations
* ✅ Synced and plain lyrics support

### 📱 UI/UX Features
* ✅ Modern Material Design 3 interface
* ✅ Dedicated equalizer screen with visual sliders
* ✅ Preset selection chips for quick access
* ✅ Dynamic theming with system integration
* ✅ Improved navigation with sidebar and tabs
* ✅ Enhanced player interface with visual feedback
* ✅ Pitch control slider with real-time feedback

### 🛠️ Technical Features
* ✅ Comprehensive testing suite
* ✅ Production-ready logging framework
* ✅ Improved code quality and maintainability
* ✅ Cross-platform audio consistency (Android, Windows, Linux)
* ✅ Better error handling and recovery
* ✅ Performance optimizations

### 🎯 Core Music Features
* ✅ Play songs from YouTube/YouTube Music
* ✅ Song caching while playing
* ✅ Radio feature support
* ✅ Background music playback
* ✅ Playlist creation & bookmark support
* ✅ Artist & Album bookmark support
* ✅ Import songs, playlists, albums, artists via sharing from YouTube/YouTube Music
* ✅ Streaming quality control
* ✅ Song downloading support
* ✅ Multi-language support
* ✅ Sleep timer
* ✅ No advertisements
* ✅ No login required
* ✅ Piped playlist integration
* ✅ Android Auto support

## 📱 Platforms

* Android (Primary focus with Media Kit backend)
* Windows (Media Kit support)
* Linux (Media Kit support)

## 📦 Dependencies

All original dependencies plus:
* Enhanced Media Kit integration for audio processing
* Proper logging framework implementation
* AudioFlux for musical key detection
* Modern Flutter packages for better UI/UX

## 🙏 Credits & Acknowledgments

This project is a fork of [Harmony Music](https://github.com/anandnet/Harmony-Music) by [anandnet](https://github.com/anandnet).

### Original Project Credits:
* [Flutter documentation](https://docs.flutter.dev/) - Best guide for cross-platform UI/app development
* [Suragch](https://suragch.medium.com/) - Articles related to Just Audio & state management
* [sigma67](https://github.com/sigma67) - Unofficial YouTube Music API project
* [vfsfitvnm](https://github.com/vfsfitvnm) - ViMusic app UI inspiration
* [LRCLIB](https://lrclib.net) - Synced lyrics provider
* [Piped](https://piped.video) - Playlist integration

### Original Major Packages:
* just_audio: ^0.9.40 - Audio player for Android
* media_kit: ^1.1.9 - Audio player for Linux and Windows
* audio_service: ^0.18.15 - Background music & platform audio services
* get: ^4.6.6 - State management, dependency injection, and routing
* youtube_explode_dart: ^2.0.2 - Third-party package for song URLs
* hive: ^2.2.3 - Offline database
* hive_flutter: ^1.1.0

## 📄 License

Harmonic Music maintains the same licensing as the original Harmony Music:

```
Harmony Music is free software licensed under GPL v3.0 with the following conditions:

- Copied/Modified versions of this software cannot be used for 'non-free' and profit purposes.
- You cannot publish copied/modified versions of this app on closed-source app repositories
  like PlayStore/AppStore.
```

## 🚨 Disclaimer

```
This project has been created while learning, and learning is the main intention.
This project is not sponsored or affiliated with, funded, authorized, endorsed by any content provider.
Any song, content, trademark used in this app are intellectual property of their respective owners.
Harmonic Music is not responsible for any infringement of copyright or other intellectual property rights that may result
from the use of the songs and other content available through this app.

This Software is released "as-is", without any warranty, responsibility or liability.
In no event shall the Author of this Software be liable for any special, consequential,
incidental or indirect damages whatsoever (including, without limitation, any 
other pecuniary loss) arising out of the use of inability to use this product, even if
Author of this Software is aware of the possibility of such damages and known defect.
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

For support, please open an issue on the GitHub repository.