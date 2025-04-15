# CBT603
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 603 is from Sebastian Welton, and contains a powerful     *   FILE 603
//*           pds scanning tool called QWIKSCAN, which is meant     *   FILE 603
//*           to run under TSO/ISPF.                                *   FILE 603
//*                                                                 *   FILE 603
//*           email:    sebastian@welton.de                         *   FILE 603
//*           website:  www.welton.de                               *   FILE 603
//*                                                                 *   FILE 603
//*     Short description:                                          *   FILE 603
//*                                                                 *   FILE 603
//*     Basically QWIKSCAN is a low level, high performance PDS     *   FILE 603
//*     scanning utility that will perform character-by-character   *   FILE 603
//*     comparisons of PDS members for up to 234 bytes of user      *   FILE 603
//*     data. User data is defined as:                              *   FILE 603
//*                                                                 *   FILE 603
//*     * Up to 78 bytes of 'if' data                               *   FILE 603
//*     * Up to 78 bytes of 'and' data                              *   FILE 603
//*     * Up to 78 bytes of 'or' data                               *   FILE 603
//*                                                                 *   FILE 603
//*     In addition to this the user may enhance the performance    *   FILE 603
//*     of QWIKSCAN by means of giving it delimiting 'stop after'   *   FILE 603
//*     instructions in either its regular mode of operation or     *   FILE 603
//*     it's super-locate mode.                                     *   FILE 603
//*                                                                 *   FILE 603
//*     While QWIKSCAN is running, the user's terminal is           *   FILE 603
//*     updated after the first 50 and every subsequent 50 PDS      *   FILE 603
//*     members are processed.  The updated panel will tell the     *   FILE 603
//*     user how many members have been processed so far, and       *   FILE 603
//*     how many successful matches have been located.              *   FILE 603
//*                                                                 *   FILE 603
//*     Assuming that at least one successful match has been        *   FILE 603
//*     made, a temporary ISPF table is updated with the member     *   FILE 603
//*     name, ISPF statistics, etc. and when the search completes   *   FILE 603
//*     this table will be presented to the user.  They may then    *   FILE 603
//*     select any or all displayed members (multiple row selects   *   FILE 603
//*     are honoured.)                                              *   FILE 603
//*                                                                 *   FILE 603
//*     If a member is selected for processing, QWIKSCAN will       *   FILE 603
//*     initiate an ISPF BROWSE session with the nominated          *   FILE 603
//*     member(s).  Prior to displaying the member, QWIKSCAN will   *   FILE 603
//*     pre-format the control line of the BROWSE panel with the    *   FILE 603
//*     command required to find the user 'if' character string.    *   FILE 603
//*     So, all the user has to do to locate the data they are      *   FILE 603
//*     interested in, is to press ENTER and use the RFIND key      *   FILE 603
//*     to display further occurrences, if any.                     *   FILE 603
//*                                                                 *   FILE 603
//*     As a rough guide to performance, QWIKSCAN requires about    *   FILE 603
//*     0.9 seconds, elapsed time, to search a PDS member fixed     *   FILE 603
//*     at 80 bytes, containing approximately 80 lines of data      *   FILE 603
//*     for a 4 byte search string (and not finding it.)  Having    *   FILE 603
//*     said this the processing time is ultimately dependent       *   FILE 603
//*     upon machine type, IPS settings, allocated SU's, etc.  It   *   FILE 603
//*     is possible, as explained later, to instruct QWIKSCAN to    *   FILE 603
//*     operate far quicker than this.                              *   FILE 603
```
