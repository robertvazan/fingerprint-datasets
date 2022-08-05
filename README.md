# Fingerprint dataset collection

Curated collection of human fingerprint datasets suitable for research and evaluation of fingerprint recognition algorithms.

- [Dataset classification](#dataset-classification)
- [Public rectangular datasets](#public-rectangular-datasets)
    - [FVC2000 DB1 B](#fvc2000-db1-b)
    - [FVC2000 DB2 B](#fvc2000-db2-b)
    - [FVC2000 DB3 B](#fvc2000-db3-b)
    - [FVC2000 DB4 B](#fvc2000-db4-b)
    - [FVC2002 DB1 B](#fvc2002-db1-b)
    - [FVC2002 DB2 B](#fvc2002-db2-b)
    - [FVC2002 DB3 B](#fvc2002-db3-b)
    - [FVC2002 DB4 B](#fvc2002-db4-b)
    - [FVC2004 DB1 B](#fvc2004-db1-b)
    - [FVC2004 DB2 B](#fvc2004-db2-b)
    - [FVC2004 DB3 B](#fvc2004-db3-b)
    - [FVC2004 DB4 B](#fvc2004-db4-b)
    - [Neurotechnology CrossMatch](#neurotechnology-crossmatch)
    - [Neurotechnology UareU](#neurotechnology-uareu)
    - [FVS dataset](#fvs-dataset)
    - [Tsinghua Palmprint Database](#tsinghua-palmprint-database)
- [Licensed rectangular datasets](#licensed-rectangular-datasets)
    - [CASIA-FingerprintV5](#casia-fingerprintv5)
    - [NIST Special Database 302](#nist-special-database-302)
    - [NIST Special Database 301 A](#nist-special-database-301-a)
    - [CASIA-PalmprintV1](#casia-palmprintv1)
    - [CASIA-MS-PalmprintV1](#casia-ms-palmprintv1)
    - [FVC2006 DB1](#fvc2006-db1)
    - [FVC2006 DB2](#fvc2006-db2)
    - [FVC2006 DB3](#fvc2006-db3)
    - [FVC2006 DB4](#fvc2006-db4)
    - [FVC2000 DB1 A](#fvc2000-db1-a)
    - [FVC2000 DB2 A](#fvc2000-db2-a)
    - [FVC2000 DB3 A](#fvc2000-db3-a)
    - [FVC2000 DB4 A](#fvc2000-db4-a)
    - [FVC2002 DB1 A](#fvc2002-db1-a)
    - [FVC2002 DB2 A](#fvc2002-db2-a)
    - [FVC2002 DB3 A](#fvc2002-db3-a)
    - [FVC2002 DB4 A](#fvc2002-db4-a)
    - [FVC2004 DB1 A](#fvc2004-db1-a)
    - [FVC2004 DB2 A](#fvc2004-db2-a)
    - [FVC2004 DB3 A](#fvc2004-db3-a)
    - [FVC2004 DB4 A](#fvc2004-db4-a)
- [Public pairsets](#public-pairsets)
    - [MINEX validation dataset](#minex-validation-dataset)
- [Licensed pairsets](#licensed-pairsets)
    - [NIST Special Database 300](#nist-special-database-300)
- [Licensed latent datasets](#licensed-latent-datasets)
    - [NIST Special Database 302 E](#nist-special-database-302-e)
    - [NIST Special Database 301 B](#nist-special-database-301-b)
- [Public unpaired datasets](#public-unpaired-datasets)
    - [SOCOFing](#socofing)
- [Secret datasets](#secret-datasets)
- [Generators](#generators)
- [Other lists](#other-lists)

## Dataset classification

By access:

- public - Available for download by anyone without any explicit restrictions on use or redistribution. Where implicit copyright applies, publisher appears to be uninterested in enforcing it.
- licensed - Available only after accepting license that contains confidentiality terms. This includes all datasets that cost money. License may include other restrictions in addition to confidentiality.
- secret - Secret dataset itself cannot be obtained, but algorithms can be submitted for evaluation on the dataset. All competition datasets are secret to prevent cheating.

By impression count:

- rectangular dataset - There are more than two impressions per finger. Rectangular datasets have certain advantages in research due to the large number of matching pairs.
- pairset - There are two impressions per finger. All natural datasets and thus all large datasets are pairsets.
- latent dataset - Latent datasets contain latent fingerprints taken from objects. They typically do not identify finger, only subject. They are usually intended to be matched against plain/rolled fingerprints from another dataset.
- unpaired - Unpaired datasets contain only one impression of every finger. They have somewhat limited applications.

## Public rectangular datasets

### FVC2000 DB1 B

Small sample of FVC2000 DB1, one of the four datasets used in [FVC2000](http://bias.csr.unibo.it/fvc2000/default.asp) competition.

- Size: 10 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 300x300px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2000/download.asp), [direct download](http://bias.csr.unibo.it/fvc2000/Downloads/DB1_B.zip)
- Documentation: [FVC2000 datasets](http://bias.csr.unibo.it/fvc2000/databases.asp)
- Population: white students
- Enrollment: unmoderated
- Sensor: optical, 500dpi, Secure Desktop Scanner by KeyTronic

### FVC2000 DB2 B

Small sample of FVC2000 DB2, one of the four datasets used in [FVC2000](http://bias.csr.unibo.it/fvc2000/default.asp) competition.

- Size: 10 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 256x364px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2000/download.asp), [direct download](http://bias.csr.unibo.it/fvc2000/Downloads/DB2_B.zip)
- Documentation: [FVC2000 datasets](http://bias.csr.unibo.it/fvc2000/databases.asp)
- Population: white students
- Enrollment: unmoderated
- Sensor: capacitive, 500dpi, TouchChip by ST Microelectronics

### FVC2000 DB3 B

Small sample of FVC2000 DB3, one of the four datasets used in [FVC2000](http://bias.csr.unibo.it/fvc2000/default.asp) competition.

- Size: 10 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 448x478px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2000/download.asp), [direct download](http://bias.csr.unibo.it/fvc2000/Downloads/DB3_B.zip)
- Documentation: [FVC2000 datasets](http://bias.csr.unibo.it/fvc2000/databases.asp)
- Population: white, 5-73 years
- Enrollment: partial QA
- Sensor: optical, 500dpi, DF-90 by Identicator Technology

### FVC2000 DB4 B

Small sample of FVC2000 DB4, one of the four datasets used in [FVC2000](http://bias.csr.unibo.it/fvc2000/default.asp) competition. This dataset is synthetic.

- Size: 10 fingers x 8 impressions
- Impression type: synthetic plain
- Format: TIFF, 500dpi, 240x320px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2000/download.asp), [direct download](http://bias.csr.unibo.it/fvc2000/Downloads/DB4_B.zip)
- Documentation: [FVC2000 datasets](http://bias.csr.unibo.it/fvc2000/databases.asp)
- Generator: unknown

### FVC2002 DB1 B

Small sample of FVC2002 DB1, one of the four datasets used in [FVC2002](http://bias.csr.unibo.it/fvc2002/) competition.

- Size: 10 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 388x374px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2002/download.asp), [direct download](http://bias.csr.unibo.it/fvc2002/Downloads/DB1_B.zip)
- Documentation: [FVC2002 datasets](http://bias.csr.unibo.it/fvc2002/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: optical, 500dpi, TouchView II by Identix

### FVC2002 DB2 B

Small sample of FVC2002 DB2, one of the four datasets used in [FVC2002](http://bias.csr.unibo.it/fvc2002/) competition.

- Size: 10 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 569dpi, 296x560px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2002/download.asp), [direct download](http://bias.csr.unibo.it/fvc2002/Downloads/DB2_B.zip)
- Documentation: [FVC2002 datasets](http://bias.csr.unibo.it/fvc2002/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: optical, 569dpi, FX2000 by Biometrika

### FVC2002 DB3 B

Small sample of FVC2002 DB3, one of the four datasets used in [FVC2002](http://bias.csr.unibo.it/fvc2002/) competition.

- Size: 10 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 300x300px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2002/download.asp), [direct download](http://bias.csr.unibo.it/fvc2002/Downloads/DB3_B.zip)
- Documentation: [FVC2002 datasets](http://bias.csr.unibo.it/fvc2002/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: capacitive, 500dpi, 100 SC by Precise Biometrics

### FVC2002 DB4 B

Small sample of FVC2002 DB4, one of the four datasets used in [FVC2002](http://bias.csr.unibo.it/fvc2002/) competition. This dataset is synthetic.

- Size: 10 fingers x 8 impressions
- Impression type: synthetic plain
- Format: TIFF, 500dpi, 288x384px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2002/download.asp), [direct download](http://bias.csr.unibo.it/fvc2002/Downloads/DB4_B.zip)
- Documentation: [FVC2002 datasets](http://bias.csr.unibo.it/fvc2002/databases.asp)
- Generator: [SFinGe](http://biolab.csr.unibo.it/research.asp?organize=Activities&select=&selObj=12&pathSubj=111%7C%7C12&) v2.51

### FVC2004 DB1 B

Small sample of FVC2004 DB1, one of the four datasets used in [FVC2004](http://bias.csr.unibo.it/fvc2004/) competition.

- Size: 10 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 640x480px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2004/download.asp), [direct download](http://bias.csr.unibo.it/fvc2004/Downloads/DB1_B.zip)
- Documentation: [FVC2004 datasets](http://bias.csr.unibo.it/fvc2004/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: optical, 500dpi, V300 by CrossMatch

### FVC2004 DB2 B

Small sample of FVC2004 DB2, one of the four datasets used in [FVC2004](http://bias.csr.unibo.it/fvc2004/) competition.

- Size: 10 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 328x364px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2004/download.asp), [direct download](http://bias.csr.unibo.it/fvc2004/Downloads/DB2_B.zip)
- Documentation: [FVC2004 datasets](http://bias.csr.unibo.it/fvc2004/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: optical, 500dpi, U.are.U 4000 by Digital Persona

### FVC2004 DB3 B

Small sample of FVC2004 DB3, one of the four datasets used in [FVC2004](http://bias.csr.unibo.it/fvc2004/) competition.

- Size: 10 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 512dpi, 300x480px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2004/download.asp), [direct download](http://bias.csr.unibo.it/fvc2004/Downloads/DB3_B.zip)
- Documentation: [FVC2004 datasets](http://bias.csr.unibo.it/fvc2004/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: thermal sweep, 512dpi, FingerChip FCD4B14CB by Atmel

### FVC2004 DB4 B

Small sample of FVC2004 DB4, one of the four datasets used in [FVC2004](http://bias.csr.unibo.it/fvc2004/) competition. This dataset is synthetic.

- Size: 10 fingers x 8 impressions
- Impression type: synthetic plain
- Format: TIFF, 500dpi, 288x384px
- License: unspecified, free download
- Download: [download page](http://bias.csr.unibo.it/fvc2004/download.asp), [direct download](http://bias.csr.unibo.it/fvc2004/Downloads/DB4_B.zip)
- Documentation: [FVC2004 datasets](http://bias.csr.unibo.it/fvc2004/databases.asp)
- Generator: [SFinGe](http://biolab.csr.unibo.it/research.asp?organize=Activities&select=&selObj=12&pathSubj=111%7C%7C12&) v3.0

### Neurotechnology CrossMatch

One of two sample datasets distributed by Neurotechnology.

- Size: 51 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 504x480px
- License: unspecified, free download
- Download: [download page](https://www.neurotechnology.com/download.html#databases), [direct download](https://www.neurotechnology.com/download/CrossMatch_Sample_DB.zip)
- Sensor: optical, 500dpi, Verifier 300 by Cross Match Technologies

### Neurotechnology UareU

One of two sample datasets distributed by Neurotechnology.

- Size: 65 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 326x357px
- License: unspecified, free download
- Download: [download page](https://www.neurotechnology.com/download.html#databases), [direct download](https://www.neurotechnology.com/download/UareU_sample_DB.zip)
- Sensor: optical, 500dpi, U.are.U 4000 by DigitalPersona

### FVS dataset

Small rectangular dataset shared by Shivang Patel as part of his [Fingerprint Verification System](http://fvs.sourceforge.net/about.html) project.

- Size: 21 fingers x 8 impressions
- Impression type: plain
- Format: BMP, 256x256px, unknown DPI
- License: unspecified, free download
- Download: [download page](http://fvs.sourceforge.net/download.html), [direct download](http://fvs.sourceforge.net/fingerprint_bitmaps.zip)

### Tsinghua Palmprint Database

Tsinghua Palmprint Database (THUPALMLAB) contains palm prints without fingers.

- Size: 80 subjects x 2 palms x 8 impressions
- Impression type: palm
- Format: BMP, 500dpi, 2040x2040px
- License: for noncommercial research
- Download: [download page](http://ivg.au.tsinghua.edu.cn/dataset/THUPALMLAB.php), [direct download](http://ivg.au.tsinghua.edu.cn/dataset/samples_THUPALMLAB/THUPALMLAB.rar)
- Documentation: [paper](http://ivg.au.tsinghua.edu.cn/dataset/samples_THUPALMLAB/Robust%20and%20efficient%20ridge-based%20palmprint%20matching.pdf)
- Sensor: Hisign

## Licensed rectangular datasets

### CASIA-FingerprintV5

Large dataset collected by Chinese Academy of Sciences.

- Size: 500 subjects x 8 fingers x 5 impressions
- Impression type: plain
- Format: BMP, 512dpi, 328x356px
- License: bundled in [dataset description](http://www.idealtest.org/dbDetailForUser.do?id=7#/datasetDetail/7), prohibits publishing and redistribution
- Download: [download page](http://www.idealtest.org/dbDetailForUser.do?id=7#/datasetDetail/7) (requires signup)
- Documentation: [attached on download page](http://www.idealtest.org/dbDetailForUser.do?id=7#/datasetDetail/7)
- Population: Chinese graduate students, workers, waiters, ...
- Enrollment: artificial difficulty
- Sensor: "URU4000" (probably U.are.U 4000 by Digital Persona, optical, 512dpi)

### NIST Special Database 302

Live fingerprint dataset collected by NIST using a wide variety of sensors. It also includes latent fingerprints that have [their own entry](#nist-special-database-302-e) in this list.

- Size: 200 subjects x 10 fingers x 12-18 impressions
- Impression type: plain, rolled, 4-finger, 2-thumb, palm
- Format: PNG, 500-1000dpi
- License: [simple confidentiality rules](https://nigos.nist.gov/datasets/sd302/request)
- Download: via [request page](https://nigos.nist.gov/datasets/sd302/request)
- Documentation: [overview page](https://www.nist.gov/itl/iad/image-group/nist-special-database-302), [user guide](https://nvlpubs.nist.gov/nistpubs/TechnicalNotes/NIST.TN.2007.pdf)
- Population: volunteers from US
- Enrollment: moderated
- Sensor: 15 sensor types (7 optical, 3 solid-state, 5 touch-free)

### NIST Special Database 301 A

Live fingerprint dataset collected by NIST using a wide variety of sensors.

- Size: 51 subjects x 10 fingers x 14-15 impressions
- Impression type: plain, rolled, 4-finger, 2-thumb, palm
- Format: PNG, 500-1000dpi
- License: [simple confidentiality rules](https://nigos.nist.gov/datasets/sd301/request)
- Download: via [request page](https://nigos.nist.gov/datasets/sd301/request)
- Documentation: [overview page](https://www.nist.gov/itl/iad/image-group/nist-special-database-301), [user guide](https://nvlpubs.nist.gov/nistpubs/TechnicalNotes/NIST.TN.2002.pdf)
- Population: volunteers from US
- Enrollment: moderated
- Sensor: 10 sensor types (5 optical, 2 solid-state, 3 touch-free)

### CASIA-PalmprintV1

Palmprint dataset collected by Chinese Academy of Sciences. No friction ridges.

- Size: 312 subjects x 2 hands x 8 impressions
- Impression type: contactless palm without friction ridges
- Format: grayscale JPEG, 640x480px, variable DPI
- License: bundled in [dataset description](http://www.idealtest.org/dbDetailForUser.do?id=5#/datasetDetail/5), prohibits publishing and redistribution
- Download: [download page](http://www.idealtest.org/dbDetailForUser.do?id=5#/datasetDetail/5) (requires signup)
- Documentation: [attached on download page](http://www.idealtest.org/dbDetailForUser.do?id=5#/datasetDetail/5)
- Sensor: custom

### CASIA-MS-PalmprintV1

Multispectral hand dataset collected by Chinese Academy of Sciences. No friction ridges.

- Size: 100 subjects x 2 hands x 6 impressions x 6 wavelengths
- Impression type: contactless hand without friction ridges
- Format: grayscale JPEG, 768x576px, variable DPI
- License: bundled in [dataset description](http://www.idealtest.org/dbDetailForUser.do?id=6#/datasetDetail/6), prohibits publishing and redistribution
- Download: [download page](http://www.idealtest.org/dbDetailForUser.do?id=6#/datasetDetail/6) (requires signup)
- Documentation: [attached on download page](http://www.idealtest.org/dbDetailForUser.do?id=6#/datasetDetail/6)
- Enrollment: pegs control hand position
- Sensor: custom

### FVC2006 DB1

One of the four datasets used in [FVC2006](http://bias.csr.unibo.it/fvc2006/default.asp) competition. It is split into A (140 fingers) and B (10 fingers) subsets.

- Size: 150 fingers x 12 impressions
- Impression type: plain
- Format: BMP, 250dpi, 96x96px
- License: signed 2-year [license agreement](http://atvs.ii.uam.es/atvs/licenses/FVC2006_License.pdf)
- Download: see [instructions](http://atvs.ii.uam.es/atvs/fvc2006.html)
- Documentation: [FVC2006 datasets](http://bias.csr.unibo.it/fvc2006/databases.asp)
- Population: white volunteers
- Enrollment: unmoderated
- Sensor: electric field sensor, 250dpi

### FVC2006 DB2

One of the four datasets used in [FVC2006](http://bias.csr.unibo.it/fvc2006/default.asp) competition. It is split into A (140 fingers) and B (10 fingers) subsets.

- Size: 150 fingers x 12 impressions
- Impression type: plain
- Format: BMP, 569dpi, 400x560px
- License: signed 2-year [license agreement](http://atvs.ii.uam.es/atvs/licenses/FVC2006_License.pdf)
- Download: see [instructions](http://atvs.ii.uam.es/atvs/fvc2006.html)
- Documentation: [FVC2006 datasets](http://bias.csr.unibo.it/fvc2006/databases.asp)
- Population: white volunteers
- Enrollment: unmoderated
- Sensor: electric field sensor, 250dpi

### FVC2006 DB3

One of the four datasets used in [FVC2006](http://bias.csr.unibo.it/fvc2006/default.asp) competition. It is split into A (140 fingers) and B (10 fingers) subsets.

- Size: 150 fingers x 12 impressions
- Impression type: sweep
- Format: BMP, 500dpi, 400x500px
- License: signed 2-year [license agreement](http://atvs.ii.uam.es/atvs/licenses/FVC2006_License.pdf)
- Download: see [instructions](http://atvs.ii.uam.es/atvs/fvc2006.html)
- Documentation: [FVC2006 datasets](http://bias.csr.unibo.it/fvc2006/databases.asp)
- Population: white volunteers
- Enrollment: unmoderated
- Sensor: electric field sensor, 250dpi

### FVC2006 DB4

One of the four datasets used in [FVC2006](http://bias.csr.unibo.it/fvc2006/default.asp) competition. It is split into A (140 fingers) and B (10 fingers) subsets.

- Size: 150 fingers x 12 impressions
- Impression type: synthetic plain
- Format: BMP, 500dpi, 288x384px
- License: signed 2-year [license agreement](http://atvs.ii.uam.es/atvs/licenses/FVC2006_License.pdf)
- Download: see [instructions](http://atvs.ii.uam.es/atvs/fvc2006.html)
- Documentation: [FVC2006 datasets](http://bias.csr.unibo.it/fvc2006/databases.asp)
- Generator: [SFinGe](http://biolab.csr.unibo.it/research.asp?organize=Activities&select=&selObj=12&pathSubj=111%7C%7C12&) v3.0

### FVC2000 DB1 A

The larger, hidden part of FVC2000 DB1, one of the four datasets used in [FVC2000](http://bias.csr.unibo.it/fvc2000/default.asp) competition.

- Size: 100 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 300x300px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2000 datasets](http://bias.csr.unibo.it/fvc2000/databases.asp)
- Population: white students
- Enrollment: unmoderated
- Sensor: optical, 500dpi, Secure Desktop Scanner by KeyTronic

### FVC2000 DB2 A

The larger, hidden part of FVC2000 DB2, one of the four datasets used in [FVC2000](http://bias.csr.unibo.it/fvc2000/default.asp) competition.

- Size: 100 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 256x364px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2000 datasets](http://bias.csr.unibo.it/fvc2000/databases.asp)
- Population: white students
- Enrollment: unmoderated
- Sensor: capacitive, 500dpi, TouchChip by ST Microelectronics

### FVC2000 DB3 A

The larger, hidden part of FVC2000 DB3, one of the four datasets used in [FVC2000](http://bias.csr.unibo.it/fvc2000/default.asp) competition.

- Size: 100 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 448x478px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2000 datasets](http://bias.csr.unibo.it/fvc2000/databases.asp)
- Population: white, 5-73 years
- Enrollment: partial QA
- Sensor: optical, 500dpi, DF-90 by Identicator Technology

### FVC2000 DB4 A

The larger, hidden part of FVC2000 DB4, one of the four datasets used in [FVC2000](http://bias.csr.unibo.it/fvc2000/default.asp) competition. This dataset is synthetic.

- Size: 100 fingers x 8 impressions
- Impression type: synthetic plain
- Format: TIFF, 500dpi, 240x320px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2000 datasets](http://bias.csr.unibo.it/fvc2000/databases.asp)
- Generator: unknown

### FVC2002 DB1 A

The larger, hidden part of FVC2002 DB1, one of the four datasets used in [FVC2002](http://bias.csr.unibo.it/fvc2002/) competition.

- Size: 100 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 388x374px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2002 datasets](http://bias.csr.unibo.it/fvc2002/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: optical, 500dpi, TouchView II by Identix

### FVC2002 DB2 A

The larger, hidden part of FVC2002 DB2, one of the four datasets used in [FVC2002](http://bias.csr.unibo.it/fvc2002/) competition.

- Size: 100 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 569dpi, 296x560px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2002 datasets](http://bias.csr.unibo.it/fvc2002/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: optical, 569dpi, FX2000 by Biometrika

### FVC2002 DB3 A

The larger, hidden part of FVC2002 DB3, one of the four datasets used in [FVC2002](http://bias.csr.unibo.it/fvc2002/) competition.

- Size: 100 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 300x300px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2002 datasets](http://bias.csr.unibo.it/fvc2002/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: capacitive, 500dpi, 100 SC by Precise Biometrics

### FVC2002 DB4 A

The larger, hidden part of FVC2002 DB4, one of the four datasets used in [FVC2002](http://bias.csr.unibo.it/fvc2002/) competition. This dataset is synthetic.

- Size: 100 fingers x 8 impressions
- Impression type: synthetic plain
- Format: TIFF, 500dpi, 288x384px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2002 datasets](http://bias.csr.unibo.it/fvc2002/databases.asp)
- Generator: [SFinGe](http://biolab.csr.unibo.it/research.asp?organize=Activities&select=&selObj=12&pathSubj=111%7C%7C12&) v2.51

### FVC2004 DB1 A

The larger, hidden part of FVC2004 DB1, one of the four datasets used in [FVC2004](http://bias.csr.unibo.it/fvc2004/) competition.

- Size: 100 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 640x480px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2004 datasets](http://bias.csr.unibo.it/fvc2004/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: optical, 500dpi, V300 by CrossMatch

### FVC2004 DB2 A

The larger, hidden part of FVC2004 DB2, one of the four datasets used in [FVC2004](http://bias.csr.unibo.it/fvc2004/) competition.

- Size: 100 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 500dpi, 328x364px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2004 datasets](http://bias.csr.unibo.it/fvc2004/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: optical, 500dpi, U.are.U 4000 by Digital Persona

### FVC2004 DB3 A

The larger, hidden part of FVC2004 DB3, one of the four datasets used in [FVC2004](http://bias.csr.unibo.it/fvc2004/) competition.

- Size: 100 fingers x 8 impressions
- Impression type: plain
- Format: TIFF, 512dpi, 300x480px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2004 datasets](http://bias.csr.unibo.it/fvc2004/databases.asp)
- Population: white students
- Enrollment: artificial difficulty
- Sensor: thermal sweep, 512dpi, FingerChip FCD4B14CB by Atmel

### FVC2004 DB4 A

The larger, hidden part of FVC2004 DB4, one of the four datasets used in [FVC2004](http://bias.csr.unibo.it/fvc2004/) competition. This dataset is synthetic.

- Size: 100 fingers x 8 impressions
- Impression type: synthetic plain
- Format: TIFF, 500dpi, 288x384px
- Cost: [~140€](http://bias.csr.unibo.it/maltoni/handbook/) (includes all 12 FVC datasets and a book)
- Documentation: [FVC2004 datasets](http://bias.csr.unibo.it/fvc2004/databases.asp)
- Generator: [SFinGe](http://biolab.csr.unibo.it/research.asp?organize=Activities&select=&selObj=12&pathSubj=111%7C%7C12&) v3.0

## Public pairsets

### MINEX validation dataset

Small public dataset that can be used to prepare submissions to [MINEX competition](https://www.nist.gov/itl/iad/image-group/minutiae-interoperability-exchange-minex-iii). Part of [MINEX validation tool](https://github.com/usnistgov/minex/tree/master/minexiii/validation).

- Size: 50 subjects x 10 fingers x 2 impressions
- Impression type: plain
- Format: raw grayscale, [separate metadata](https://github.com/usnistgov/minex/blob/master/minexiii/validation/minexiii_validation_data.h), 500dpi
- License: [permissive](https://github.com/usnistgov/minex/blob/master/LICENSE.md)
- Download: [GitHub](https://github.com/usnistgov/minex/tree/master/minexiii/validation/validation_imagery_raw)

## Licensed pairsets

### NIST Special Database 300

Segmented scanned fingerprint cards from US law enforcement. This is technically a single impression dataset, but since every finger is present twice as rolled and flat impression, the dataset can be considered a pairset.

- Size: 888 subjects x 10 fingers x 2 impressions
- Impression type: plain, rolled, 4-finger
- Format: PNG, 500/1000/2000dpi
- License: [simple confidentiality rules](https://nigos.nist.gov/datasets/sd300/request)
- Download: via [request page](https://nigos.nist.gov/datasets/sd300/request)
- Documentation: [overview page](https://www.nist.gov/itl/iad/image-group/nist-special-database-300), [user guide](https://nvlpubs.nist.gov/nistpubs/TechnicalNotes/NIST.TN.1993.pdf)
- Population: arrested US citizens
- Enrollment: controlled but with some uncooperative subjects
- Technology: scanned ink

## Licensed latent datasets

### NIST Special Database 302 E

Dataset of latent fingerprints of subjects from [NIST Special Database 302](#nist-special-database-302). Latent fingerprints from this dataset are supposed to be matched with plain/rolled fingerprints from NIST Special Database 302.

- Size: 200 subjects x 50 impressions
- Impression type: latent, finger and palm
- Format: PNG, 1000-1500dpi
- License: [simple confidentiality rules](https://nigos.nist.gov/datasets/sd302/request)
- Download: via [request page](https://nigos.nist.gov/datasets/sd302/request)
- Documentation: [overview page](https://www.nist.gov/itl/iad/image-group/nist-special-database-302), [user guide](https://nvlpubs.nist.gov/nistpubs/TechnicalNotes/NIST.TN.2007.pdf)
- Population: volunteers from US, subjects identical to NIST Special Database 302
- Activity: variety of activities that result in latent fingerprints
- Technology: variety of latent fingerprint collection methods

### NIST Special Database 301 B

Dataset of latent fingerprints of subjects from [NIST Special Database 301 A](#nist-special-database-301-a). Latent fingerprints from this dataset are supposed to be matched with plain/rolled fingerprints from NIST Special Database 301 A.

- Size: 24 subjects x 50 impressions
- Impression type: latent, finger and palm
- Format: PNG, 1000-1500dpi
- License: [simple confidentiality rules](https://nigos.nist.gov/datasets/sd301/request)
- Download: via [request page](https://nigos.nist.gov/datasets/sd301/request)
- Documentation: [overview page](https://www.nist.gov/itl/iad/image-group/nist-special-database-301), [user guide](https://nvlpubs.nist.gov/nistpubs/TechnicalNotes/NIST.TN.2002.pdf)
- Population: volunteers from US, subset of subjects from NIST Special Database 301 A
- Activity: variety of activities that result in latent fingerprints
- Technology: variety of latent fingerprint collection methods

## Public unpaired datasets

### SOCOFing

Sokoto Coventry Fingerprint Dataset (SOCOFing) is a single impression dataset. Images are tagged with gender and finger position. Real images are complemented with synthetically damaged versions.

- Size: 600 subjects x 10 fingers x 1 impression
- Impression type: plain
- Format: BMP, 500dpi, 96x103px
- License: for noncommercial research, see [paper](https://arxiv.org/pdf/1807.10609.pdf)
- Download: [Kaggle](https://www.kaggle.com/datasets/ruizgara/socofing)
- Documentation: [Arxiv paper](https://arxiv.org/pdf/1807.10609.pdf)
- Population: African
- Sensor: Hamster Plus (HSDU03P), SecuGen SDU03P

## Secret datasets

Datasets of some of these competitions might overlap. There's no way to know for sure, so all competitions are listed.

- [FVC-onGoing Fingerprint Verification (FV)](https://biolab.csr.unibo.it/FVCOnGoing/UI/Form/BenchmarkAreas/BenchmarkAreaFV.aspx)
- [FVC-onGoing Palmprint Verification (PV)](https://biolab.csr.unibo.it/FVCOnGoing/UI/Form/BenchmarkAreas/BenchmarkAreaPV.aspx)
- [FVC-onGoing Fingerprint Matching (FMISO)](https://biolab.csr.unibo.it/FVCOnGoing/UI/Form/BenchmarkAreas/BenchmarkAreaFMISO.aspx)
- [FVC-onGoing Fingerprint Indexing (FIDX)](https://biolab.csr.unibo.it/FVCOnGoing/UI/Form/BenchmarkAreas/BenchmarkAreaFIDX.aspx)
- [FVC-onGoing Fingerprint Orientation Extraction (FOE)](https://biolab.csr.unibo.it/FVCOnGoing/UI/Form/BenchmarkAreas/BenchmarkAreaFOE.aspx)
- [FVC-onGoing Secure Template Fingerprint Verification (STFV)](https://biolab.csr.unibo.it/FVCOnGoing/UI/Form/BenchmarkAreas/BenchmarkAreaSTFV.aspx)
- [NIST Minutiae Interoperability Exchange (MINEX)](https://www.nist.gov/itl/iad/image-group/minutiae-interoperability-exchange-minex-iii)
- [NIST Slap Fingerprint Segmentation Evaluation (SlapSeg)](https://www.nist.gov/itl/iad/image-group/slap-fingerprint-segmentation-evaluation-iii)
- [NIST Proprietary Fingerprint Template (PFT)](https://www.nist.gov/itl/iad/image-group/proprietary-fingerprint-template-pft-iii)
- [NIST Evaluation of Latent Friction Ridge Technology (ELFT)](https://www.nist.gov/itl/iad/image-group/evaluation-latent-friction-ridge-technology)

## Generators

- [SFinGe](http://biolab.csr.unibo.it/research.asp?organize=Activities&select=&selObj=12&pathSubj=111%7C%7C12&)

## Other lists

- :star: [NIST Biometric and Forensic Research Database Catalog](https://tsapps.nist.gov/BDbC/Search)
- [Luigi Rosa's list](http://www.advancedsourcecode.com/fingerprintdatabase.asp)
- [CVonline](https://homepages.inf.ed.ac.uk/rbf/CVonline/Imagedbase.htm#fingerprints)
- [NIST Special Databases](https://www.nist.gov/itl/iad/image-group/resources/biometric-special-databases-and-software)
- [FVC2000](http://bias.csr.unibo.it/fvc2000/download.asp), [FVC2002](http://bias.csr.unibo.it/fvc2002/download.asp), [FVC2004](http://bias.csr.unibo.it/fvc2004/download.asp)

## Contribute

If you have something to add or correct here, please submit a PR or open an issue.

## Legal

Every dataset has its own license. This [CC0](LICENSE) list was created by Robert Važan while working on [SourceAFIS](https://sourceafis.machinezoo.com/).
