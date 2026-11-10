# 274 nhạc cụ SoundFont riêng biệt

Tách từ GeneralUser-GS.sf2 theo 274 preset đang được mapping trong app. Mỗi file chứa một preset, đủ sample và instrument nội bộ phụ thuộc; giữ nguyên bank/program (đánh số từ 0), PCM16, loop, tuning, zones, modulators và liên kết stereo.

Tên file: `inst_b000_p004.sf2`; icon tương ứng: `ic_inst_b000_p004`.

Tổng dung lượng SF2: **147.29 MB**, chưa tính các file metadata. File gốc có 287 preset; 13 preset không có trong catalog app được liệt kê trong manifest, không xuất ra SF2.

`manifest.json` chứa tên, ID app, nhóm, bank/program, icon, file, dung lượng và SHA-256. `validation.json` ghi phạm vi kiểm tra. Giấy phép gốc nằm trong từng SF2 và GeneralUser-LICENSE.txt.

Đây là dữ liệu SoundFont cho synth, không phải các bản ghi WAV. Nếu phục vụ qua URL, dấu cách trong thư mục `sound segmented` cần được mã hóa thành `%20`.

Kiểm tra native: **274/274 file nạp và render thành công** bằng thư viện FluidSynth/JNI của app trên Android giả lập API 34, ở 22.050 Hz. Mỗi preset thử 3 nốt, velocity 100; tất cả có tín hiệu và không có NaN/Infinity. Đây không phải kiểm tra mọi cao độ/velocity layer. Chi tiết trong `native-validation.json`.

| File | Nhạc cụ | Nhóm | KB |
| --- | --- | --- | ---: |
| `inst_b000_p004.sf2` | Tine Electric Piano | Piano | 382.56 |
| `inst_b000_p000.sf2` | Grand Piano | Piano | 2178.86 |
| `inst_b000_p001.sf2` | Bright Grand Piano | Piano | 2178.76 |
| `inst_b000_p002.sf2` | Electric Grand Piano | Piano | 2331.88 |
| `inst_b000_p003.sf2` | Honky-Tonk Piano | Piano | 2390.16 |
| `inst_b000_p005.sf2` | FM Electric Piano | Piano | 374.67 |
| `inst_b000_p006.sf2` | Harpsichord | Piano | 243.11 |
| `inst_b000_p007.sf2` | Clavinet | Piano | 282.73 |
| `inst_b008_p004.sf2` | Chorused Tine EP | Piano | 382.63 |
| `inst_b008_p005.sf2` | Chorused FM EP | Piano | 375.46 |
| `inst_b008_p006.sf2` | Coupled Harpsichord | Piano | 243.12 |
| `inst_b011_p000.sf2` | Piano & Str.-Fade | Piano | 4632.82 |
| `inst_b011_p001.sf2` | Piano & Str.-Sus | Piano | 4632.79 |
| `inst_b011_p004.sf2` | Tine & FM EPs | Piano | 754.75 |
| `inst_b011_p005.sf2` | Piano & FM EP | Piano | 2551.66 |
| `inst_b011_p006.sf2` | Harpsichord noVel | Piano | 243.11 |
| `inst_b012_p000.sf2` | Bell Piano | Piano | 2531.65 |
| `inst_b012_p004.sf2` | Bell Tine EP | Piano | 734.79 |
| `inst_b012_p006.sf2` | Coupled Harpsi noVel | Piano | 243.12 |
| `inst_b000_p012.sf2` | Marimba | Chromatic percussion | 57.35 |
| `inst_b000_p014.sf2` | Tubular Bells | Chromatic percussion | 578.84 |
| `inst_b000_p010.sf2` | Music Box | Chromatic percussion | 88.58 |
| `inst_b000_p008.sf2` | Celeste | Chromatic percussion | 88.26 |
| `inst_b000_p009.sf2` | Glockenspiel | Chromatic percussion | 82.71 |
| `inst_b000_p011.sf2` | Vibraphone | Chromatic percussion | 107.99 |
| `inst_b000_p013.sf2` | Xylophone | Chromatic percussion | 65.75 |
| `inst_b000_p015.sf2` | Dulcimer | Chromatic percussion | 471.36 |
| `inst_b008_p014.sf2` | Church Bells | Chromatic percussion | 578.88 |
| `inst_b009_p014.sf2` | Carillon | Chromatic percussion | 11.35 |
| `inst_b011_p008.sf2` | Tinkling Bells | Chromatic percussion | 3.50 |
| `inst_b011_p011.sf2` | Vibraphone No Trem. | Chromatic percussion | 107.98 |
| `inst_b011_p014.sf2` | Bell Tower | Chromatic percussion | 589.83 |
| `inst_b012_p010.sf2` | Christmas Bells | Chromatic percussion | 7.84 |
| `inst_b000_p088.sf2` | Fantasia | Synth pad | 403.36 |
| `inst_b000_p089.sf2` | Warm Pad | Synth pad | 2456.46 |
| `inst_b000_p090.sf2` | Polysynth | Synth pad | 535.56 |
| `inst_b000_p091.sf2` | Space Voice | Synth pad | 179.09 |
| `inst_b000_p092.sf2` | Bowed Glass | Synth pad | 383.08 |
| `inst_b000_p093.sf2` | Metal Pad | Synth pad | 586.14 |
| `inst_b000_p094.sf2` | Halo Pad | Synth pad | 654.86 |
| `inst_b000_p095.sf2` | Sweep Pad | Synth pad | 535.56 |
| `inst_b011_p088.sf2` | Harpsi Pad | Synth pad | 482.44 |
| `inst_b011_p089.sf2` | Solar Wind | Synth pad | 58.10 |
| `inst_b012_p088.sf2` | Fantasia 2 | Synth pad | 29.34 |
| `inst_b012_p089.sf2` | Solar Wind 2 | Synth pad | 58.09 |
| `inst_b013_p088.sf2` | Night Vision | Synth pad | 278.13 |
| `inst_b000_p024.sf2` | Nylon Guitar | Guitar | 423.37 |
| `inst_b000_p025.sf2` | Steel Guitar | Guitar | 410.60 |
| `inst_b000_p026.sf2` | Jazz Guitar | Guitar | 290.93 |
| `inst_b000_p027.sf2` | Clean Guitar | Guitar | 549.63 |
| `inst_b000_p028.sf2` | Muted Guitar | Guitar | 54.60 |
| `inst_b000_p029.sf2` | Overdrive Guitar | Guitar | 893.66 |
| `inst_b000_p030.sf2` | Distortion Guitar | Guitar | 839.48 |
| `inst_b000_p031.sf2` | Guitar Harmonics | Guitar | 37.05 |
| `inst_b008_p024.sf2` | Ukulele | Guitar | 15.14 |
| `inst_b008_p025.sf2` | 12-String Guitar | Guitar | 411.64 |
| `inst_b008_p026.sf2` | Hawaiian Guitar | Guitar | 3.28 |
| `inst_b008_p027.sf2` | Chorused Clean Gt. | Guitar | 549.74 |
| `inst_b008_p028.sf2` | Funk Guitar | Guitar | 613.25 |
| `inst_b008_p030.sf2` | Feedback Guitar | Guitar | 840.35 |
| `inst_b008_p031.sf2` | Guitar Feedback | Guitar | 3.47 |
| `inst_b011_p029.sf2` | Wah Guitar (CC21) | Guitar | 893.68 |
| `inst_b012_p027.sf2` | Clean Guitar 2 | Guitar | 957.39 |
| `inst_b016_p025.sf2` | Mandolin | Guitar | 325.31 |
| `inst_b000_p073.sf2` | Flute | Pipe | 813.08 |
| `inst_b000_p072.sf2` | Piccolo | Pipe | 157.65 |
| `inst_b000_p074.sf2` | Recorder | Pipe | 229.09 |
| `inst_b000_p075.sf2` | Pan Flute | Pipe | 76.73 |
| `inst_b000_p076.sf2` | Bottle Blow | Pipe | 84.22 |
| `inst_b000_p077.sf2` | Shakuhachi | Pipe | 152.32 |
| `inst_b000_p078.sf2` | Whistle | Pipe | 243.71 |
| `inst_b000_p079.sf2` | Ocarina | Pipe | 249.41 |
| `inst_b011_p078.sf2` | Whistlin' | Pipe | 251.47 |
| `inst_b024_p075.sf2` | Tin Whistle | Pipe | 83.54 |
| `inst_b025_p075.sf2` | Tin Whistle Nm | Pipe | 83.52 |
| `inst_b026_p075.sf2` | Tin Whistle Or | Pipe | 83.52 |
| `inst_b000_p048.sf2` | Fast Strings | Ensemble | 2457.35 |
| `inst_b000_p049.sf2` | Slow Strings | Ensemble | 2457.35 |
| `inst_b000_p050.sf2` | Synth Strings 1 | Ensemble | 258.25 |
| `inst_b000_p051.sf2` | Synth Strings 2 | Ensemble | 178.78 |
| `inst_b000_p052.sf2` | Concert Choir | Ensemble | 753.84 |
| `inst_b000_p053.sf2` | Voice Oohs | Ensemble | 563.94 |
| `inst_b000_p054.sf2` | Synth Voice | Ensemble | 399.29 |
| `inst_b000_p055.sf2` | Orchestra Hit | Ensemble | 79.75 |
| `inst_b001_p048.sf2` | Fast Strings Mono | Ensemble | 2457.42 |
| `inst_b001_p049.sf2` | Slow Strings Mono | Ensemble | 2457.34 |
| `inst_b001_p052.sf2` | Concert Choir Mono | Ensemble | 753.30 |
| `inst_b008_p048.sf2` | Orchestra Pad | Ensemble | 3406.56 |
| `inst_b008_p050.sf2` | Synth Strings 3 | Ensemble | 258.54 |
| `inst_b011_p049.sf2` | Velo Strings | Ensemble | 2457.28 |
| `inst_b011_p050.sf2` | Synth Strings 4 | Ensemble | 23.00 |
| `inst_b011_p051.sf2` | Synth Strings 5 | Ensemble | 22.97 |
| `inst_b012_p048.sf2` | Full Orchestra | Ensemble | 4691.20 |
| `inst_b012_p049.sf2` | Velo Strings Mono | Ensemble | 2457.37 |
| `inst_b013_p048.sf2` | Woodwind Choir | Ensemble | 1528.00 |
| `inst_b000_p038.sf2` | Synth Bass 1 | Bass | 34.99 |
| `inst_b000_p039.sf2` | Synth Bass 2 | Bass | 297.77 |
| `inst_b000_p032.sf2` | Acoustic Bass | Bass | 68.60 |
| `inst_b000_p033.sf2` | Finger Bass | Bass | 103.16 |
| `inst_b000_p034.sf2` | Pick Bass | Bass | 155.44 |
| `inst_b000_p035.sf2` | Fretless Bass | Bass | 133.64 |
| `inst_b000_p036.sf2` | Slap Bass 1 | Bass | 92.05 |
| `inst_b000_p037.sf2` | Slap Bass 2 | Bass | 101.96 |
| `inst_b001_p038.sf2` | Synth Bass 101 | Bass | 20.37 |
| `inst_b008_p038.sf2` | Acid Bass | Bass | 20.48 |
| `inst_b008_p039.sf2` | Beef FM Bass | Bass | 369.17 |
| `inst_b011_p038.sf2` | Techno Bass | Bass | 32.27 |
| `inst_b011_p039.sf2` | Pulse Bass | Bass | 17.45 |
| `inst_b012_p038.sf2` | Mean Saw Bass | Bass | 43.52 |
| `inst_b000_p080.sf2` | Square Lead | Synth lead | 20.51 |
| `inst_b000_p081.sf2` | Saw Lead | Synth lead | 20.55 |
| `inst_b000_p082.sf2` | Synth Calliope | Synth lead | 117.53 |
| `inst_b000_p083.sf2` | Chiffer Lead | Synth lead | 290.89 |
| `inst_b000_p084.sf2` | Charang | Synth lead | 754.15 |
| `inst_b000_p085.sf2` | Solo Vox | Synth lead | 64.28 |
| `inst_b000_p086.sf2` | 5th Saw Wave | Synth lead | 176.43 |
| `inst_b000_p087.sf2` | Bass & Lead | Synth lead | 52.99 |
| `inst_b001_p080.sf2` | Square Wave | Synth lead | 20.28 |
| `inst_b001_p081.sf2` | Saw Wave | Synth lead | 20.30 |
| `inst_b008_p080.sf2` | Sine Wave | Synth lead | 8.48 |
| `inst_b008_p081.sf2` | Doctor Solo | Synth lead | 34.98 |
| `inst_b011_p081.sf2` | Sawtooth Stab | Synth lead | 20.37 |
| `inst_b012_p080.sf2` | Square Lead 2 | Synth lead | 20.35 |
| `inst_b012_p081.sf2` | Saw Lead 2 | Synth lead | 20.37 |
| `inst_b013_p080.sf2` | Square Lead 3 | Synth lead | 20.33 |
| `inst_b013_p081.sf2` | Saw Lead 3 | Synth lead | 20.38 |
| `inst_b000_p065.sf2` | Alto Sax | Reed | 505.14 |
| `inst_b000_p064.sf2` | Soprano Sax | Reed | 280.97 |
| `inst_b000_p066.sf2` | Tenor Sax | Reed | 397.33 |
| `inst_b000_p067.sf2` | Baritone Sax | Reed | 198.13 |
| `inst_b000_p068.sf2` | Oboe | Reed | 325.20 |
| `inst_b000_p069.sf2` | English Horn | Reed | 302.85 |
| `inst_b000_p070.sf2` | Bassoon | Reed | 510.45 |
| `inst_b000_p071.sf2` | Clarinet | Reed | 55.03 |
| `inst_b000_p016.sf2` | Tonewheel Organ | Organ | 42.87 |
| `inst_b000_p017.sf2` | Percussive Organ | Organ | 196.92 |
| `inst_b000_p018.sf2` | Rock Organ | Organ | 228.13 |
| `inst_b000_p019.sf2` | Pipe Organ | Organ | 674.76 |
| `inst_b000_p020.sf2` | Reed Organ | Organ | 218.39 |
| `inst_b000_p021.sf2` | Accordion | Organ | 218.24 |
| `inst_b000_p022.sf2` | Harmonica | Organ | 65.00 |
| `inst_b000_p023.sf2` | Bandoneon | Organ | 218.18 |
| `inst_b008_p016.sf2` | Detuned Tnwl. Organ | Organ | 42.89 |
| `inst_b008_p017.sf2` | Detuned Perc. Organ | Organ | 196.94 |
| `inst_b008_p019.sf2` | Pipe Organ 2 | Organ | 714.90 |
| `inst_b008_p021.sf2` | Italian Accordion | Organ | 218.14 |
| `inst_b011_p016.sf2` | Tonewheel Org noVel | Organ | 42.86 |
| `inst_b011_p017.sf2` | Percussive Org noVel | Organ | 196.91 |
| `inst_b011_p018.sf2` | Rock Organ noVel | Organ | 228.12 |
| `inst_b011_p019.sf2` | Pipe Organ noVel | Organ | 674.75 |
| `inst_b011_p020.sf2` | Reed Organ noVel | Organ | 218.38 |
| `inst_b012_p016.sf2` | Detun Tnwl Org noVel | Organ | 42.88 |
| `inst_b012_p017.sf2` | Detun Perc Org noVel | Organ | 196.93 |
| `inst_b012_p019.sf2` | Pipe Organ 2 noVel | Organ | 714.89 |
| `inst_b000_p040.sf2` | Violin | Strings | 940.00 |
| `inst_b000_p041.sf2` | Viola | Strings | 777.27 |
| `inst_b000_p042.sf2` | Cello | Strings | 1010.97 |
| `inst_b000_p043.sf2` | Double Bass | Strings | 601.32 |
| `inst_b000_p044.sf2` | Tremolo Strings | Strings | 2457.31 |
| `inst_b000_p045.sf2` | Pizzicato Strings | Strings | 138.29 |
| `inst_b000_p046.sf2` | Orchestral Harp | Strings | 309.05 |
| `inst_b000_p047.sf2` | Timpani | Strings | 228.03 |
| `inst_b001_p044.sf2` | Tremolo Strings Mono | Strings | 2456.49 |
| `inst_b000_p056.sf2` | Trumpet | Brass | 148.81 |
| `inst_b000_p057.sf2` | Trombone | Brass | 160.15 |
| `inst_b000_p058.sf2` | Tuba | Brass | 192.24 |
| `inst_b000_p059.sf2` | Muted Trumpet | Brass | 302.36 |
| `inst_b000_p060.sf2` | French Horns | Brass | 511.92 |
| `inst_b000_p061.sf2` | Brass Section | Brass | 921.91 |
| `inst_b000_p062.sf2` | Synth Brass 1 | Brass | 20.68 |
| `inst_b000_p063.sf2` | Synth Brass 2 | Brass | 21.44 |
| `inst_b001_p056.sf2` | Trumpet 2 | Brass | 148.98 |
| `inst_b001_p057.sf2` | Trombone 2 | Brass | 160.24 |
| `inst_b001_p060.sf2` | Solo French Horn | Brass | 361.57 |
| `inst_b001_p061.sf2` | Brass Section Mono | Brass | 921.63 |
| `inst_b008_p061.sf2` | Brass Section 2 | Brass | 1225.52 |
| `inst_b008_p062.sf2` | Synth Brass 3 | Brass | 4.39 |
| `inst_b008_p063.sf2` | Synth Brass 4 | Brass | 30.59 |
| `inst_b011_p061.sf2` | Brass Section 3 | Brass | 350.26 |
| `inst_b000_p096.sf2` | Ice Rain | Synth effects | 326.88 |
| `inst_b000_p097.sf2` | Soundtrack | Synth effects | 432.07 |
| `inst_b000_p098.sf2` | Crystal | Synth effects | 139.16 |
| `inst_b000_p099.sf2` | Atmosphere | Synth effects | 599.21 |
| `inst_b000_p100.sf2` | Brightness | Synth effects | 329.33 |
| `inst_b000_p101.sf2` | Goblin | Synth effects | 127.26 |
| `inst_b000_p102.sf2` | Echo Drops | Synth effects | 470.36 |
| `inst_b000_p103.sf2` | Star Theme | Synth effects | 725.48 |
| `inst_b001_p098.sf2` | Synth Mallet | Synth effects | 128.01 |
| `inst_b002_p102.sf2` | Echo Pan | Synth effects | 20.86 |
| `inst_b011_p096.sf2` | Mystery Pad | Synth effects | 30.53 |
| `inst_b011_p098.sf2` | Synth Chime | Synth effects | 5.54 |
| `inst_b011_p100.sf2` | Bright Saw Stack | Synth effects | 258.32 |
| `inst_b000_p104.sf2` | Sitar | Ethnic | 486.81 |
| `inst_b000_p105.sf2` | Banjo | Ethnic | 218.10 |
| `inst_b000_p106.sf2` | Shamisen | Ethnic | 33.12 |
| `inst_b000_p107.sf2` | Koto | Ethnic | 350.04 |
| `inst_b000_p108.sf2` | Kalimba | Ethnic | 27.61 |
| `inst_b000_p109.sf2` | Bagpipes | Ethnic | 73.14 |
| `inst_b000_p110.sf2` | Fiddle | Ethnic | 940.00 |
| `inst_b000_p111.sf2` | Shenai | Ethnic | 12.95 |
| `inst_b008_p107.sf2` | Taisho Koto | Ethnic | 757.94 |
| `inst_b000_p112.sf2` | Tinker Bell | Percussive | 26.82 |
| `inst_b000_p113.sf2` | Agogo | Percussive | 19.09 |
| `inst_b000_p114.sf2` | Steel Drums | Percussive | 59.20 |
| `inst_b000_p115.sf2` | Wood Block | Percussive | 17.72 |
| `inst_b000_p116.sf2` | Taiko Drum | Percussive | 27.00 |
| `inst_b000_p117.sf2` | Melodic Tom | Percussive | 538.99 |
| `inst_b000_p118.sf2` | Synth Drum | Percussive | 32.99 |
| `inst_b000_p119.sf2` | Reverse Cymbal | Percussive | 81.69 |
| `inst_b008_p115.sf2` | Castanets | Percussive | 6.28 |
| `inst_b008_p116.sf2` | Concert Bass Drum | Percussive | 128.48 |
| `inst_b008_p117.sf2` | Melodic Tom 2 | Percussive | 161.74 |
| `inst_b008_p118.sf2` | 808 Tom | Percussive | 7.73 |
| `inst_b011_p119.sf2` | Cymbal Crash | Percussive | 458.76 |
| `inst_b012_p119.sf2` | Tambourine | Percussive | 16.43 |
| `inst_b000_p120.sf2` | Fret Noise | Sound effects | 18.61 |
| `inst_b000_p121.sf2` | Breath Noise | Sound effects | 22.26 |
| `inst_b000_p122.sf2` | Seashore | Sound effects | 44.85 |
| `inst_b000_p123.sf2` | Birds | Sound effects | 219.06 |
| `inst_b000_p124.sf2` | Telephone 1 | Sound effects | 6.53 |
| `inst_b000_p125.sf2` | Helicopter | Sound effects | 28.88 |
| `inst_b000_p126.sf2` | Applause | Sound effects | 182.04 |
| `inst_b000_p127.sf2` | Gun Shot | Sound effects | 23.84 |
| `inst_b001_p120.sf2` | Cut Noise | Sound effects | 8.76 |
| `inst_b001_p121.sf2` | Fl. Key Click | Sound effects | 3.54 |
| `inst_b001_p122.sf2` | Rain | Sound effects | 149.84 |
| `inst_b001_p123.sf2` | Dog | Sound effects | 22.42 |
| `inst_b001_p124.sf2` | Telephone 2 | Sound effects | 9.36 |
| `inst_b001_p125.sf2` | Car-Engine | Sound effects | 80.25 |
| `inst_b001_p126.sf2` | Laughing | Sound effects | 52.34 |
| `inst_b001_p127.sf2` | Machine Gun | Sound effects | 23.85 |
| `inst_b002_p120.sf2` | String Slap | Sound effects | 9.29 |
| `inst_b002_p122.sf2` | Thunder | Sound effects | 81.80 |
| `inst_b002_p123.sf2` | Horse Gallop | Sound effects | 43.77 |
| `inst_b002_p124.sf2` | Door Creaking | Sound effects | 60.24 |
| `inst_b002_p125.sf2` | Car-Stop | Sound effects | 44.59 |
| `inst_b002_p126.sf2` | Scream | Sound effects | 53.42 |
| `inst_b002_p127.sf2` | Lasergun | Sound effects | 238.39 |
| `inst_b003_p122.sf2` | Wind | Sound effects | 237.99 |
| `inst_b003_p123.sf2` | Bird 2 | Sound effects | 3.19 |
| `inst_b003_p124.sf2` | Door | Sound effects | 29.98 |
| `inst_b003_p125.sf2` | Car-Pass | Sound effects | 88.41 |
| `inst_b003_p126.sf2` | Punch | Sound effects | 33.13 |
| `inst_b003_p127.sf2` | Explosion | Sound effects | 40.21 |
| `inst_b004_p122.sf2` | Stream | Sound effects | 144.60 |
| `inst_b004_p124.sf2` | Scratch | Sound effects | 23.31 |
| `inst_b004_p125.sf2` | Car-Crash | Sound effects | 92.98 |
| `inst_b004_p126.sf2` | Heart Beat | Sound effects | 45.10 |
| `inst_b005_p122.sf2` | Bubbles | Sound effects | 56.78 |
| `inst_b005_p124.sf2` | Windchime | Sound effects | 49.26 |
| `inst_b005_p125.sf2` | Siren | Sound effects | 19.04 |
| `inst_b005_p126.sf2` | Footsteps | Sound effects | 10.60 |
| `inst_b006_p125.sf2` | Train | Sound effects | 60.54 |
| `inst_b007_p125.sf2` | Jet Plane | Sound effects | 50.16 |
| `inst_b008_p125.sf2` | Starship | Sound effects | 23.89 |
| `inst_b009_p125.sf2` | Burst Noise | Sound effects | 254.06 |
| `inst_b011_p121.sf2` | Filter Snap | Sound effects | 6.60 |
| `inst_b011_p122.sf2` | Howling Winds | Sound effects | 19.66 |
| `inst_b011_p127.sf2` | Interference | Sound effects | 6.74 |
| `inst_b012_p122.sf2` | White Noise Wave | Sound effects | 237.94 |
| `inst_b012_p127.sf2` | Shooting Star | Sound effects | 238.00 |
| `inst_b128_p000.sf2` | Standard 1 | Drum kits | 2837.42 |
| `inst_b128_p001.sf2` | Standard 2 | Drum kits | 2692.93 |
| `inst_b128_p002.sf2` | Standard 3 | Drum kits | 2700.41 |
| `inst_b128_p008.sf2` | Room | Drum kits | 2844.71 |
| `inst_b128_p016.sf2` | Power | Drum kits | 3107.98 |
| `inst_b128_p024.sf2` | Electronic | Drum kits | 2443.85 |
| `inst_b128_p025.sf2` | 808/909 | Drum kits | 1782.23 |
| `inst_b128_p026.sf2` | Dance | Drum kits | 2443.97 |
| `inst_b128_p032.sf2` | Jazz | Drum kits | 2684.10 |
| `inst_b128_p040.sf2` | Brush | Drum kits | 2697.70 |
| `inst_b128_p048.sf2` | Orchestral | Drum kits | 2387.76 |
| `inst_b128_p056.sf2` | SFX | Drum kits | 2124.23 |
| `inst_b128_p127.sf2` | CM-64/32L | Drum kits | 4314.10 |
