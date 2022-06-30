
# Awesome-Audio [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome audio technology resources for developers

- [Code](#code)
- [Community](#community)
- [Education](#education)
- [Hardware](#hardware)
- [Industry](#industry)
- [Research](#research)

[![Gitter](https://badges.gitter.im/DolbyIO/awesome-audio.svg)](https://gitter.im/DolbyIO/awesome-audio?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# Code

Software applications, tools, and APIs you can use to solve audio-related problems to use in your own awesome audio projects.

- [How-To Analyze Audio](#how-to-analyze-audio)
- [How-To Edit Audio](#how-to-edit-audio)
- [How-To Playback Audio](#how-to-playback-audio)
- [How-To Read and Write Audio Files](#how-to-read-and-write-audio-files)
- [How-To Record Audio](#how-to-record-audio)
- [How-To Send Real-Time Audio](#how-to-send-real-time-audio)
- [How-To Transcribe Audio](#how-to-transcribe-audio)
- [How-To Visualize Audio](#how-to-visualize-audio)


## How-To Analyze Audio

- **APIs**
    - [Dolby.io Media Analyze API](https://dolby.io/products/analyze/) - services to analyze an audio file to identify codec, clipping, loudness, sound classification, silence, etc. Also has options force Speech, and Diagnostics.
- **Apps**
    - [MATLAB DSP System Toolbox](https://www.mathworks.com/products/dsp-system.html) - application for designing, simulating, and analyzing signal processing systems
- **Python**
    - [Librosa](https://librosa.org/doc/latest/index.html) - python package for music and audio analysis
    - [PyAudio Analysis](https://github.com/tyiannak/pyAudioAnalysis) - python package for audio analysis and feature extraction

## How-To Edit Audio

- **APIs**
    - [Dolby.io Media Enhance API](https://dolby.io/products/enhance/) - services to enhance media such as correcting audio impurities like noise, sibilance, equalization, tonality, loudness
    - [Dolby.io Media Transcode API](https://dolby.io/products/transcode/) - Convert and assemble content that looks and sounds great no matter the device or where it’s viewed. With support for high resolution, high frame rates, and web and streaming formats.
    - [Dolby.io Media Music Mastering API](https://dolby.io/products/music-mastering/) - Get professional-sounding audio masters that keep your creative intent intact with the powerful Music Mastering API from Dolby.io — the result of thousands of hours of musical analysis.
- **Apps**
    - [Avid Pro Tools](https://www.avid.com/pro-tools) - music software to create audio recording, composing, editing, and mastering
    - [iZotope](https://www.izotope.com/en/products.html) - audio software for music production and post production, composing, editing, and mastering
    - [FL Studio](https://www.image-line.com/) - DAW for MacOS and Windows
    - [Ableton Live](https://www.ableton.com/en/live/) - DAW for MacOS and Windows
    - [Nuendo](https://www.steinberg.net/nuendo/) - DAW for MacOS and Windows that has support for Dolby Atmos and other forms of spatial audio
    - [Logic Pro](https://www.apple.com/logic-pro/) - Logic Pro is a digital audio workstation and MIDI sequencer software application for  macOS
    - [Garageband](https://www.apple.com/mac/garageband/) - Free tool for MacOS users to record and edit audio
    - [Audacity](https://www.audacityteam.org/) - Audacity is a free and open-source digital audio editor and recording application software
    - [Reaper](https://www.reaper.fm/) - Propietary cross platform DAW
    - [Bitwig Studio](https://www.bitwig.com/) - Cross Platform DAW made by ex-Ableton employees
    - [Ardour](https://ardour.org/) - Ardour is a hard disk recorder and digital audio workstation application that runs on Linux, macOS, FreeBSD and Microsoft Windows.
    - [LMMS](https://lmms.io/) - free, open source, cross platform DAW

## How-To Playback Audio

- **Android**
    - [AudioTrack](https://developer.android.com/reference/android/media/AudioTrack) - Android class that streams PCM audio buffers to audio hardware for playback
    - [ExoPlayer](https://exoplayer.dev/) - library for local or streaming playback of audio and video
    - [MediaPlayer](https://developer.android.com/reference/android/media/MediaPlayer) - class for controlling playback of a pre-existing audio or video file
    - [Oboe](https://github.com/google/oboe) - C++ library that wraps OpenSL ES and AAudio for high performance audio operations
- **JavaScript**
    - [Cross-Browser Audio Basics](https://developer.mozilla.org/en-US/docs/Web/Guide/Audio_and_video_delivery/Cross-browser_audio_basics) - tutorial for creating an HTML5 audio player
- **Python**
    - [PyAudio](https://people.csail.mit.edu/hubert/pyaudio/#downloads) - python bindings for PortAudio to interface with audio drivers to record or playback audido (Open-Source/MIT)


## How-To Read and Write Audio Files

- **CLI**
    - [ffmpeg](http://ffmpeg.org/) - A complete, cross-platform solution to record, convert and stream audio and video.
    - [GStreamer](https://gstreamer.freedesktop.org/) - library for constructing graphs of media-handling components
    - [mpv](https://mpv.io/) - mpv is a free (as in freedom) media player for the command line. It supports a wide variety of media file formats, audio and video codecs, and subtitle types.
    - [VLC](https://www.videolan.org/) - VLC is a free and open source cross-platform multimedia player and framework that plays most multimedia files as well as DVDs, Audio CDs, VCDs, and various streaming protocols.
    - [Handbrake](https://handbrake.fr/) - HandBrake is a tool for converting video from nearly any format to a selection of modern, widely supported codecs.
    - [Sound eXchange](http://sox.sourceforge.net/) - SoX is billed as the swiss army knife of sound processing programs
- **Python**
    - [pyAV](http://docs.mikeboers.com/pyav/) - python bindings for ffmpeg to access media via containers, streams, packets, codecs, and frames


## How-To Record Audio

- **Android**
    - [AudioRecord](https://developer.android.com/reference/android/media/AudioRecord) - Android class for reading buffers of raw audio data from audio hardware
    - [MediaRecorder](https://developer.android.com/reference/android/media/MediaRecorder) - records encoded audio or video and saves the recording to an output file
    - [Oboe](https://github.com/google/oboe) - C++ library that wraps OpenSL ES and AAudio for high performance audio operations compatible across API levels
- **JavaScript**
    - [MediaRecorder](https://developer.mozilla.org/en-US/docs/Web/API/MediaRecorder) - Web API for processing a stream of media content such as audio tracks
    - [react-mic](https://hackingbeauty.github.io/react-mic/) - javascript / react library to record audio cross-platform
- **Python**
    - [PyAudio](https://people.csail.mit.edu/hubert/pyaudio/#downloads) - python bindings for PortAudio to interface with audio drivers to record or playback audido (Open-Source/MIT)
- **Swift**
    - [AVFoundation](https://developer.apple.com/documentation/avfoundation) - framework for audiovisual assets, control devices, audio processing, and system audio interactions
         - [AVCapture](https://developer.apple.com/documentation/avfoundation/avcapturedevice) - device, input, session, and output classes for a graph processing architecture allowing buffer analysis and processing (including video support)
    - [AVFAudio](https://developer.apple.com/documentation/avfaudio) - foundation framework to play, record, and process audio and configure system behavior
        - [AVAudioRecorder](https://developer.apple.com/documentation/avfoundation/avaudiorecorder) - class to record audio to a file and may be simplest when getting started
        - [AVAudioEngine](https://developer.apple.com/documentation/avfaudio/avaudioengine) - group of audio nodes to generate and process audio signals for input and output; does not natively support video capture but highly configurable processing nodes
    - [Audio Toolbox](https://developer.apple.com/documentation/audiotoolbox) - framework to record or play audio, convert formats, parse audio streams, and configure your audio session
- **Windows**
    - [Core Audio APIS](https://docs.microsoft.com/en-us/windows/win32/coreaudio/core-audio-apis-in-windows-vista)

## How-To Send Real-Time Audio

- **APIs**
    - [Dolby.io Communications API](https://dolby.io/products/voice-call/) - services with SDKs for adding audio and video conferencing and communications
    - [Dolby.io Streaming API](https://dolby.io/products/live-streaming/) - Millicast, acquired by Dolby, is now part of the Dolby.io platform. Millicast is a WebRTC-based real-time streaming service that enables sub-second latency, broadcast-quality color and sound, global scale, and end-to-end encryption
- **JavaScript**
    - [WebRTC API](https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API) - capture and stream audio / video media between browsers without requiring an intermediary
    - [HLS Streaming](https://developer.apple.com/streaming/) - HLS lets you deploy content using ordinary web servers and content delivery networks. HLS is designed for reliability and dynamically adapts to network conditions by optimizing playback for the available speed of wired and wireless connections.
- **Local**
    - [PulseAudio](https://www.freedesktop.org/wiki/Software/PulseAudio/) - PulseAudio is a sound server system for POSIX OSes
    - [JACK](https://jackaudio.org/) - JACK Audio Connection Kit is a professional sound server API and pair of daemon implementations to provide real-time, low-latency connections for both audio and MIDI data between applications
    - [Loopback](https://rogueamoeba.com/loopback/) - Cable-free audio routing for Mac
    - [Soundflower](https://github.com/mattingalls/Soundflower) - MacOS system extension that allows applications to pass audio to other applications.
    - [BlackHole](https://github.com/ExistentialAudio/BlackHole) - BlackHole is a modern MacOS virtual audio driver that allows applications to pass audio to other applications with zero additional latency.

## How-To Transcribe Audio

- **APIs**
    - [AWS Transcribe](https://aws.amazon.com/transcribe/) - speech to text capabilities
    - [Azure Speech-to-Text](https://azure.microsoft.com/en-us/services/cognitive-services/speech-to-text/) - transcribe audio to text
    - [Google Speech-to-Text](https://cloud.google.com/speech-to-text) - convert speech into text
    - [Symbl.ai Transcription over WebSockets](https://docs.symbl.ai/docs/streamingapi/tutorials/receive-ai-insights-from-your-web-browser) - speech to text
    - [Rev](https://www.rev.com/speech-to-text-apis) - Convert Audio & Video To Text worked on by humans
        - [rev.ai](https://www.rev.ai/) - AI branch of Rev.com
    - [Speechmatics](https://app.speechmatics.com/api-details) - Speechmatics offer a secure REST API that enables you to programatically upload audio files for processing with our different products and download the resulting transcriptions.
    - [Deepgram](https://deepgram.com/) - Build better voice applications with faster, more accurate transcription through AI Speech Recognition.
    - [Picovoice](https://picovoice.ai/) - Picovoice is the end-to-end platform for adding voice to anything on your terms.
    - [sonix](https://sonix.ai/) - Automated transcription in 35+ languages.
    - [fireflies.ai](https://fireflies.ai/) - Process audio, generate transcripts, and extract actionable data.
- **Apps**
    - [descript.com](https://www.descript.com/) - use transcripts to cut and edit video
    - [Otter.ai](https://otter.ai/login) - Generate rich notes for meetings, interviews, lectures, and other important voice conversations
- **Python**
    - [PyKaldi](https://github.com/pykaldi/pykaldi) - Python scripting layer for the Kaldi speech recognition toolkit.


## How-To Visualize Audio

- **Apps**
    - [headliner.app](https://www.headliner.app/) - create engaging social video with audio editing, transcription, and visualization
    - [getaudiogram.com](https://getaudiogram.com) - create engaging social video with audio visualizations
- **JavaScript**
    - [Wavesurfer](https://wavesurfer-js.org/) - a customizable audio waveform visualization built on Web Audio API; supporting spectrograms and other features

## Audio Plugin Development Tools
- [JUCE](https://juce.com/) - JUCE is an open-source cross-platform C++ application framework for desktop and mobile applications, including VST, VST3, AU, AUv3, RTAS and AAX audio plug-ins.
    - [react-juce](https://docs.react-juce.dev/) - React-JUCE is a hybrid JavaScript/C++ framework that enables a React.js frontend for a JUCE application or plugin.
- [iPlug2](https://iplug2.github.io/) - iPlug 2 is a simple-to-use C++ framework for developing cross platform audio plug-ins/apps and targeting multiple plug-in APIs with the same minimalistic code.
- [AudioKit](https://audiokit.io/) - AudioKit is an entire audio development ecosystem of code repositories, packages, libraries, algorithms, applications, playgorunds, tests, and scripts, built and used by a community of audio programmers, app developers, engineers, researchers, scientists, musicians, gamers, and people new to programming.
- [Plug'n Script](https://www.bluecataudio.com/Products/Product_PlugNScript/) - Blue Cat's Plug'n Script is an audio and MIDI scripting plug-in and application that can be programmed to build custom effects or virtual instruments, without quitting your favorite DAW software.
- [Faust](https://faust.grame.fr/) - Faust (Functional Audio Stream) is a functional programming language for sound synthesis and audio processing with a strong focus on the design of synthesizers, musical instruments, audio effects, etc. Faust targets high-performance signal processing applications and audio plug-ins for a variety of platforms and standards.
- [SOUL](https://soul.dev/) - The SOUL project is creating a new language and infrastructure for writing and deploying audio code. It aims to unlock improvements in latency, performance, portability and ease-of-development that aren't possible with the current mainstream techniques that are being used.
- [Max](https://cycling74.com/products/max) - Max is an infinitely flexible space to create your own interactive software



---

# Community

Social media, discussion groups, events, and audio experiences you can seek out to increase your appreciation for awesome audio.

- [Awesome Lists](#awesome-lists)
- [Collections](#collections)
- [Conferences and Events](#conferences-and-events)
- [Experiences and Places](#experiences-and-places)
- [Groups](#groups)
- [Podcasts](#podcasts)
- [Social Forums](#social-forums)

## Awesome Lists

- [awesome-scientific-audio](https://github.com/faroit/awesome-python-scientific-audio#readme) - python for scientific audio
- [awesome-sound](https://github.com/hwclass/awesome-sound) - curated list of delightful sound packages and resources
- [awesome-webaudio](https://github.com/notthetup/awesome-webaudio#readme) - curated list of awesome webaudio packages and resources
- [awesome-diarization](https://github.com/wq2012/awesome-diarization) - curated list of speaker diarization papers, libraries, datasets, and other resources

## Collections

- [Internet Archive Audio Archive](https://archive.org/details/audio) - over 14 million recordings of music, concerts, audiobooks, radio, etc.
- [Library of Congress Audio Recordings](https://www.loc.gov/audio/) - over 20,000 audio recordings of historical or cultural significance

## Conferences and Events

- [Audio Developers Conference](https://audio.dev/) - ADC is an annual event celebrating audio development technologies from music applications and game audio to audio processing andd embedded systems.  ADC's mission is to help attendees acquire and develop new skills.
- [Demuxed](https://demuxed.com/) - video-tech community event for technical topics related to video technology
- [KrankyGeek](https://www.krankygeek.com/) - annual event for WebRTC technology used for real time communications in a web browser
- [Web Audio Conference](https://webaudioconf.com/) - WAC is an international conference dedicated to web audio technologies and applications. The conference addresses academic research, artistic research, development, design, evaluation and standards concerned with emerging audio-related web technologies such as Web Audio API, Web RTC, WebSockets and Javascript.

## Experiences and Places

- [Audium](https://www.audium.org/) - sound art event in a theatre of sound-sculpted space (San Francisco)
- [ASMR University](https://asmruniversity.com/) - art & science of autonomous sensory meridian response
- [Exploratorium Listen Exhibit](https://www.exploratorium.edu/listen/index.php) - making sense of sound (San Francisco)

## Groups

- [Audio Engineering Society](https://www.aes.org/) - AES is an international organization that unites audio engineers, creative artists, scientists, and students promoting advances in audio and disseminating new knowledge and research with many local communities
- [International Society for Music Information Retrieval](https://ismir.net/about/) - ISMIR is a non-profit seeking to advance access, organization, and understanding of music information
- [Women's Audio Mission](https://womensaudiomission.org/) - WAM is a non-profit built and run by women to inspire and educate on the subject of audio in music and media

## Podcasts

- [Audio Programmer Podcast](https://theaudioprogrammer.com/) - all things audio programming, including DSP (digital signal processing), coding, and audio tech.
- [Dissect](https://dissectpodcast.com/) - Long form music analysis of albums that goes track by track discussing music theory and artist intention
- [Game Audio Podcast](http://www.gameaudiopodcast.com/) - aims to provide sound designers, composers, and everyone else interested in game audio a biweekly show
- [Song Exploder](https://songexploder.net/) - music podcast where musicians take apart their songs and tell the story of how they were made
- [Twenty Thousand Hertz](https://www.20k.org/) - the stories behind the world's most recognizable and interesting sounds

## Social Forums

- [Music and Audio Professionals](https://www.linkedin.com/groups/119984/) - LinkedIn group for audio engineers, music arrangers, music composers, etc.
- - [r/audioengineering](https://www.reddit.com/r/audioengineering/) - products, practices, and stories about the profession or hobby of recording, editing, and producing audio
- [Signal Processing StackExchange](https://dsp.stackexchange.com/) - question and answer for practioners of the art and science of signal, image, and video processing
- [The Audio Programmer Discord](https://theaudioprogrammer.com/community/) - We invite you to the Audio Programmer community, where you can connect with other audio programmers, ask questions about coding and choosing the right career path, find job opportunities and more!  

## Social Networks

- [Display](https://www.displaysocial.com/) - social platform for creators
- [Lava](https://joinlava.com) - social network for audio

## Video Channels

- [The Audio Programmer](https://www.youtube.com/theaudioprogrammer) - SOUL tutorials, JUCE tutorials, teaching audio programming for beginners, etc.

---

# Education

Resources such as books, courses, tutorials, journals, and blogs that are worth checking out to become more awesome with audio yourself.

- [Books](#books)
- [Courses](#courses)
- [Journals](#journals)
- [Tutorials & Blogs](#tutorials-and-blogs)

See something missing, view the [contribute](#contribute) section and let us know.

## Books

- Corey, Jason. (2016).  Audio Production and Critical Listening: Technical Ear Training.  Focal Press.
- Dittmar, Tim. (2017).  Audio Engineering 101: A Beginner's Guide to Music Production.  Routledge.
- Watkinson, John.  (2002).  Introduction to Digital Audio.  Focal Press.

## Courses

- [Audio Signal Processing](https://www.coursera.org/learn/audio-signal-processing) - audio signal methodologies for music.  Topics include: spectral processing techniques, transformation of sounds, analyze, synthesize, transform audio signals, python (Coursera)
- [Digital Media Foundations](https://www.linkedin.com/learning/digital-media-foundations?u=2056892) - Audio Made Simple.  Topics include creating space with channels, measuring power of sound, capturing tone as frequency, phase.  (LinkedIn Learning)
- - [Communication Acoustics](https://www.edx.org/course/communication-acoustics) - This is a comprehensive course starting from the basics: what is sound, how it propagates and prepares us gradually to learn about the human auditory system, psychoacoustics(connecting the physical world to how we perceive sounds), speech acoustics(human speech production system) and finally electroacoustics(the world of loud speakers and microphones)(Edx)
- [Fundamentals of Audio and Music Engineering](https://www.coursera.org/learn/audio-engineering) - basic concepts of acoustics and electronics and how they can be applied to understanding musical sound and make music with electronic instruments.  Topics include: sound waves, musical sound, basic electronics, and applications of these basic principles in amplifiers and speaker design (Coursera)

## Journals

- [Computer Music Journal](https://www.mitpressjournals.org/loi/comj) - a peer-reviewed academic journal that covers a wide range of topics related to digital audio signal processing and electroacoustic music
- [IEEE/ACM Transactions on Audio, Speech, and Language Processing](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6570655) - dedicated to innovative theory and methods for processing signals representing audio, speech and language, and their applications. This includes analysis, synthesis, enhancement, transformation, classification and interpretation of such signals as well as the design, development, and evaluation of associated signal processing systems
- [Journal of the Acoustical Society of America](https://asa.scitation.org/toc/jas/current) - a monthly peer-reviewed scientific journal covering aspects of acoustics
- [Journal of the Audio Engineering Society](https://www.aes.org/journal/) - peer-reviewed journal devoted to audio technology
- [SMPTE Motion Imaging Journal](https://ieeexplore.ieee.org/xpl/aboutJournal.jsp?punumber=7261654) - the key publication of the Society, providing peer-reviewed articles on topics in 3D, imaging processing, display technologies, audio, compression, digitaal cinema, and much more

## Tutorials and Blogs

- [Designing Sound](https://designingsound.org/category/tutorials/) - tutorials on the art & technique of sound design
- [ProAudioGirl](https://apriltucker.com/blog/) - Amy Tucker's blog covering audio for filmmakers, dialog editing basics, hacks & tricks, etc.
- [The Ear Training Guide for Audio Producers](https://training.npr.org/2017/01/31/the-ear-training-guide-for-audio-producers/) - NPR training guide to help identify problematic audio and prevent most common problems
- [Using ffmpeg to manipulate audio and video files](http://howto-pages.org/ffmpeg/) - How to tame the "Swiss army knife" of audio and video manipulation…

---

# Hardware

Resources for hardware considerations for recording and listening to awesome audio.


View the [contribute](#contribute) section and let us know what you think would be great resources for this section.

---

# Industry

Domains and use-case specific resources such as broadcasting, communications, gaming, music, and the web where awesome audio is applied.

- [Standards](#standards)

## Standards

- [AES Standards](https://www.aes.org/standards/) - 2-channel digital audio, MADI, analog XLR pin-out, networked audio, etc.
- [ATSC A/85](https://www.atsc.org/recommended-practice/a85-techniques-for-establishing-and-maintaining-audio-loudness-for-digital-television/) - Advanced Television Systems Committee (ATSC) Techniques for establishing and maintaining audio loudness for digital television
- [EBU R.128](https://tech.ebu.ch/docs/r/r128.pdf) - European Broadcasting Union (EBU) loudness normalisation and permitted maximum level of audio signals
- [ITU-R BS.1770](https://www.itu.int/dms_pubrec/itu-r/rec/bs/R-REC-BS.1770-4-201510-I!!PDF-E.pdf) - International Telecommunication Union (ITU) algorithms to measure audio programme loudness and true-peak audio level
- [ITU-R BS.2159-7](https://www.itu.int/dms_pub/itu-r/opb/rep/R-REP-BS.2159-7-2015-PDF-E.pdf) - International Telecommunications Union (ITU) multi-channel speaker configurations for home and broadcast applications
- [MPEG Advanced Audio Coding](https://mpeg.chiariglione.org/standards/mpeg-4/audio) - aac wideband perceptual audio coding algorithm that provides state of the art levels of compression for audio signals
- [SMPTE Audio Standards](https://ieeexplore.ieee.org/browse/standards/number/smpte?queryText=audio) - collection of standards related to audio

---

# Research

Areas of experimentation and exploration for awesome algorithms.

## Data

- [AudioSet](https://research.google.com/audioset/index.html) - large-scale dataset of manually annotated audio events with sound ontology
- [CSTR VCTK](https://datashare.is.ed.ac.uk/handle/10283/3443) - speech data uttered by 110 English speakers with various accents reading about 400 sentences from newspapers
- [Freesound](https://freesound.org/) - Freesound is a collaborative database of Creative Commons Licensed sounds.
- [LibriSpeech](http://www.openslr.org/12/) - text-to-speech training corpus with 1000 hours of English speech of read audiobooks from the LibriVox project
- [Mozilla Common Voice](https://commonvoice.mozilla.org/en/datasets) - open-source, multi-language dataset of voices to train speech-enabled applications with 68 validated hours and 18 languages
- [Netflix Open Content](https://opencontent.netflix.com/) - test titles with documentary, live action, and animation films
- [Spoken Wikipedia Corpora](https://nats.gitlab.io/swc/) - SWC is comprised of spoken articles in multiple languages
- [Voice Datasets](https://github.com/jim-schwoebel/voice_datasets) - A comprehensive list of open source voice and music datasets.

---

# Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
