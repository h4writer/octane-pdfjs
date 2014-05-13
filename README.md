Octane-pdfjs
============

There are currently two issues with the pdfjs benchmark included in the octane benchmark suite.
The first one is that the version of pdfjs is really outdated. It is created in the early days of the pdfjs project when it didn't supported a lot of functionality. As a result the benchmark doesn't test the real render speed of reading a pdf file, but the font system, which was done very poorly at that time.
Secondly the pdf included in the benchmark only includes one page. That is not a real workload of a typical pdf.

Here I updated the pdfjs revision to the v0.8.990, which is the version included in mozilla firefox 29. Also the pdf is updated to now test rendering http://www.ecma-international.org/publications/files/ECMA-ST/Ecma-262.pdf which is 258 pages long.

**Note: this is still a rough WIP.** 
