https://nickl1234567.github.io/

```bash
$gsArgs = @(
    '-sDEVICE=pdfwrite'
    '-o'
    'output.pdf'

    '-dCompatibilityLevel=1.7'
    '-dSAFER'

    '-dDownsampleColorImages=true'
    '-dColorImageDownsampleType=/Bicubic'
    '-dColorImageResolution=200'
    '-dColorImageDownsampleThreshold=1.5'

    '-dDownsampleGrayImages=true'
    '-dGrayImageDownsampleType=/Bicubic'
    '-dGrayImageResolution=200'
    '-dGrayImageDownsampleThreshold=1.5'

    '-dDownsampleMonoImages=true'
    '-dMonoImageDownsampleType=/Subsample'
    '-dMonoImageResolution=600'
    '-dMonoImageDownsampleThreshold=1.5'

    'input.pdf'
)
gswin64c.exe @gsArgs
```