# IBM AIX XL Pascal Compiler/6000

* This is IBM AIX XL Pascal Compiler/6000 V2.1.4.

* XL Pascal is unsupported (and no longer available), but functional on current (AIX 7.3) systems.

* The following documentation is available in PDF format:

  <table>
  <tr>
   <td><A HREF="https://raw.githubusercontent.com/johnsonjh/xlp/master/PDF/xlpinst.pdf">Installation Instructions</A></td>
   <td><A HREF="https://raw.githubusercontent.com/johnsonjh/xlp/master/PDF/xlpug.pdf">User's Guide</A></td>
  </tr>
  <tr>
   <td><A HREF="https://raw.githubusercontent.com/johnsonjh/xlp/master/PDF/xlpref.pdf">Language Reference</A></td>
   <td><A HREF="https://raw.githubusercontent.com/johnsonjh/xlp/master/PDF/xlplps.pdf">Specification<A></td>
  </tr>
  </table>

* Because licenses are unavailable, the following patch may be used to bypass the license manager:

  ```sh
  /usr/bin/echo -ne '\x60\x00\x00\x00' | \
    /usr/bin/dd of=/usr/lpp/xlp/lib/xlpentry bs=1 count=4 seek=2703800 conv=notrunc
  ```
