###### ToDo June 17 2016, Complete by June 24th
+ Slides
  + ~~Finish  4a~~
  + ~~Do 4b~~
  + Do 5a
  + Do 5b
  + Do 6
  + Do 7
+ Assignments
  + ~~Second half of 3~~
  + ~~Do 4~~
  + Do 5
  + Do 6
  + Do 7
+ Videos
  + ~~Do 1~~ Edit 1 together (p1, p2, p3)
  + Do 1a (MobaXterm on PC)
  + ~~Do 2~~ On youtube
  + ~~Do 3a~~ Edit 3A together (p1, p2)
  + ~~Do 3b~~ Edit beginning of 3b
  + ~~Do 4~~ On youtube
  + Do 5a
  + Do 5b
  + Do 6
  + Do 7

###### ToDo June 24th, Complete by June 30th




### Bioinformatics-Introductory-Analysis-Course
This repository contains course material for Phillip Richmond's Introduction to Bioinformatics Analysis Course

#### Course Purpose
>The purpose of this course is to provide an introduction to Bioinformatics and Genomics as it pertains to short-read sequencing analysis, with a specific focus on brewing and fermentation yeast strains.  Taught in an inverted classroom format, there will be screencasts and lecture notes for each section that can be gone through independently, and in class we will simply work on example datasets and problem sets.

#### General Course Information & Prerequisites
+ Prerequisites
  + WestGrid access is required, and is different for a PI vs. a student
    + Westgrid Account information [here](https://www.westgrid.ca/support/accounts/getting_account)
    + For a Westgrid Account, register by following these [instructions](https://www.computecanada.ca/research-portal/account-management/apply-for-an-account/).  Realize that the process can take several days! 
  + GitHub Account
    + It's free, and you can sign up [here](https://github.com/)
  + For mac/linux users, only need native terminal which comes with the operating system
  + For PC users, download and install [MobaXterm](http://mobaxterm.mobatek.net/)
    + [Advanced MobaXterm usage](https://www.youtube.com/watch?v=Gkl8LD1rwlU)
+ General Course Info
  + Videos are hosted via YouTube at Phil Richmond's YouTube Channel [here](https://www.youtube.com/channel/UC6B7cpEwSZTdbPd0d9G2JXg)
  + Slides, Assignments, and Quizzes are hosted via Google Drive [here](https://drive.google.com/drive/u/0/folders/0B3TGYF-7rCLnWjFJRVlHcVN5Nk0)
  + Extra resources:
    + [Linux/Unix Cheatsheet](https://github.com/Phillip-a-richmond/Bioinformatics-Introductory-Analysis-Course/blob/master/UnixCheatSheet.pdf)
    + [Linux/Unix online tutorial](http://www.ee.surrey.ac.uk/Teaching/Unix/)
    + Editor cheat sheets
      + [Emacs cheet sheet](http://www.rgrjr.com/emacs/emacs_cheat.html)
      + [vi cheat sheet](http://www.lagmonster.org/docs/vi.html)
      + [nano cheat sheet](http://www.codexpedia.com/text-editor/nano-text-editor-command-cheatsheet/)
    + File transfer programs
      + [Cyberduck](http://download.cnet.com/Cyberduck/3000-2160_4-10246246.html)
      + [WinSCP](https://winscp.net/eng/download.php)


#### Course Schedule
Monday July 4th, 2016.
10:00 AM - 12:00 PM.
Videos to watch before class.
Section I-1 and Section I-2

Tuesday July 5th, 2016 
10:00 AM - 12:00 PM 
Videos to watch before class: 
Section I-3a, Section I-3b, Section I-4 

Wednesday July 6th, 2016 
10:00 AM - 12:00 PM 
Videos to watch before class: 
Section I-5a, Section I-5b, and Section I-6 

Thursday July 7th, 2016
10:00 AM - 12:00 PM
Video to watch before class:
Section I-7

Friday July 8th, 2016
10:00 AM - 12:00 PM
Individual Examination



#### Course Outline
##### Section I: Introductions, Linux/Unix, WestGrid, Short Read Mapping, PBS Queue Scheduler
1. Introduction to Next Generation Sequencing, Bioinformatics, and Computing
  + [Slides](https://drive.google.com/open?id=0B3TGYF-7rCLnR3VDeENSc1NHbFU)
  + Video
2. Getting set-up on WestGrid and using terminal
  + Open up a terminal
  + Customize terminal
  + Login to WestGrid 
  + [Specs of Orcinus](https://www.westgrid.ca/support/systems/Orcinus)
  + [Slides](https://drive.google.com/open?id=0B3TGYF-7rCLnZU5TYzdZLUlXZG8)
  + Video
  + [PC User MobaXterm guide]
  + [In Class Assignment Section I-2](https://github.com/Phillip-a-richmond/Bioinformatics-Introductory-Analysis-Course/blob/master/InClassAssignmentSection2.md)
3. Exploring Linux/Unix
  + Intro to linux environment (3a)
    + ls, mkdir, cp, mv, rm, cat, more, less
    + Man pages
    + File creation
    + [Slides](https://drive.google.com/open?id=0B3TGYF-7rCLncEZPbVFqa29nWUE)
    + Video
  + Intermediate Linux commands (3b)
    + head, tail, sort, cut, paste, df, du, grep, find, permissions
    + [Slides](https://drive.google.com/open?id=0B3TGYF-7rCLnbFRFNk03V0h6QkE)
    + Video
  + [In Class Assignment Section I-3](https://github.com/Phillip-a-richmond/Bioinformatics-Introductory-Analysis-Course/blob/master/InClassAssignmentSection3.md)
  + For more practice, do [these exercises](http://www.ee.surrey.ac.uk/Teaching/Unix/index.html)
4. Advanced Linux/Unix
  + File Management
    + Compression
    + Downloading (wget)
    + Remote Copy (scp)
  + File Editing
    + vi, emacs, nano: Pick emacs
    + [Emacs cheet sheet](http://www.rgrjr.com/emacs/emacs_cheat.html)
    + [vi cheat sheet](http://www.lagmonster.org/docs/vi.html)
    + [nano cheat sheet](http://www.codexpedia.com/text-editor/nano-text-editor-command-cheatsheet/)
  + Other Secure Copy programs
    + [Cyberduck](http://download.cnet.com/Cyberduck/3000-2160_4-10246246.html)
    + [WinSCP](https://winscp.net/eng/download.php)
  + Slides
  + [Video](https://youtu.be/r9zJCo42gl8)
  + [In Class Assignment](https://github.com/Phillip-a-richmond/Bioinformatics-Introductory-Analysis-Course/blob/master/InClassAssignmentSection4.md)
5. Intro to Read Mapping
  + Bowtie2 & Samtools (5a)
    + Build genome index
    + Map paired reads
    + Interpret standard error
    + Convert bam 2 sam (samtools index)
    + Sort bam (samtools sort)
  + Organization and file types (5b)
    + Directory Hierarchies
    + FASTQ, FASTA, SAM, BAM
  + Slides
  + Video
  + In Class Assignment
6. Data visualization
  + IGV with S288c genome
  + Slides
  + Video
  + In Class Assignment
7. Interacting with the queue
  + Job Submission
  + Job Tracking
  + Slides
  + Video
  + In Class Assignment

##### In class test
> The in-class test will be an individual examination, so you won't be able to work together in groups for it.  The test will be comprehensive for all the things we learned in Section I, and if you are able to complete the assignments for each section, then the test should take only ~ 30 minutes.  You will have a 2 hour block to complete the test.  If you are unable to do so, then you won't be able to move on to Section II.  

##### Section II: Introduction to Applied Genomics: Variant Calling, Assembly, RNAseq
8. Intro to NCBI BLAST, SRA
  + Slides
  + Video
  + In Class Assignment
9. Variant Calling
  + GATK?  
  + Samtools mpileup
  + Slides
  + Video
  + In Class Assignment
10. Genome Assembly
  + Velvet
  + Abyss
  + Slides
  + Video
  + In Class Assignment
11. RNAseq
  + Bowtie2
  + HTSeq
  + DESeq2
  + EdgeR
  + Slides
  + Video
  + In Class Assignment

##### Section III: BYOD (Bring your own datasets)
This section is open to those who want to explore their own datasets and receive help with processing and data analysis.  





Feedback?  Suggestions?  Don't hesitate to contact me:

Course Instructor | Affiliation | Email Address(es) | github ID | Phone Number
--- | --- | --- | --- | ---
Phillip Richmond | PhD Student, Bioinformatics, UBC | prichmond@ubc.ca or phillip.a.richmond@gmail.com | [@Phillip-a-Richmond](https://github.com/Phillip-a-richmond) | (604)655-3595



[Test Slideshare Link](http://www.slideshare.net/PhillipAndrewRichmon/slideshelf)


