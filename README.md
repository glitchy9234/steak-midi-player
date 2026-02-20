# steak-midi-player
midi player for black midi
echo "# steak-midi-player" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/glitchy9234/steak-midi-player.git
git push -u origin mainzenith-midi-player/
├── src/
│   ├── core/
│   │   ├── midi_parser.py          (High-performance MIDI parsing)
│   │   ├── audio_engine.py         (Real-time synthesis)
│   │   └── timing_engine.py        (Precision timing)
│   ├── visualization/
│   │   ├── opengl_renderer.py      (GPU-accelerated 3D rendering)
│   │   ├── renderer.py             (Base renderer)
│   │   ├── effects.py              (Visual effects)
│   │   └── themes.py               (Color themes)
│   ├── export/
│   │   ├── video_exporter.py       (MP4/WebM/AVI export)
│   │   └── audio_exporter.py       (WAV/FLAC export)
│   ├── effects/
│   │   ├── visual_effects.py       (Bloom, blur, aberration, glow)
│   │   └── filters.py              (Color grading, tone curves)
│   ├── performance/
│   │   └── metrics.py              (FPS, load monitoring)
│   ├── ui/
│   │   ├── main_window.py          (Original UI)
│   │   ├── main_window_v2.py       (Updated GPU UI)
│   │   ├── timeline.py             (Timeline widget)
│   │   ├── controls.py             (Control widgets)
│   │   ├── export_dialog.py        (Export settings UI)
│   │   └── performance_widget.py   (Performance display)
│   └── utils/
│       ├── soundfont_manager.py    (SoundFont loading)
│       └── config.py               (Configuration)
├── tests/
├── resources/
│   ├── shaders/
│   ├── soundfonts/
│   └── themes/
├── main.py
├── requirements.txt
└── README.mdopengl_renderer.pytiming_engine.pyrenderer.pyaudio_engine.pyeffects.pythemes.pyaudio_exporter.pyvideo_exporter.pyfilters.pyvisual_effects.pymain_window.pymetrics.pytimeline.pymain_window_v2.pyexport_dialog.pycontrols.pysoundfont_manager.pyperformance_widget.pyconfig.pymain.pyrequirements.txtpython main.py
