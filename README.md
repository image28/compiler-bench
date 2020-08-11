<H2># compiler-bench
Program designed to benchmark the different compiler flags and create a website with graphs of the differerence</H2>
<BR>
Work in progress ( started ~7th-8th August 2020 )
<BR>
<HR>
<BR>
compile with<BR>
gcc timing.c [compiler options] -mavx2 -lm -Ofast -o timing<BR>
<BR>
<HR>
<BR>
<B>Compile options</B><BR>
<TABLE>
<UL>
<TR>-<TD><LI>-DALLIN</TD><TD>Compiles with all flags ( eventually )</LI></TD></TR>
<TR>-<TD><LI>-DCOMPILEDCONFIGS</TD><TD>Compiles with cached/compiled config files support</LI></TD></TR>
<TR>-<TD><LI>-DWEBSITE</TD><TD>enable generation of website</LI></TD></TR>
<TR>-<TD><LI>-DPRINTSITE</TD><TD>print the website to stdout</LI></TD></TR>
<TR>-<TD><LI>-DCOMPILER</TD><TD>set the compiler to test (e.g gcc,g++)</LI></TD></TR>
<TR>-<TD><LI>-DMAIN</TD><TD>include the main function</LI></TD></TR>
<TR>-<TD><LI>-DTIMESTAMP</TD><TD>include the timestamp function</LI></TD></TR>
<TR>-<TD><LI>-DGRAPH</TD><TD>include the graphing functions</LI></TD></TR>
<TR>-<TD><LI>-DAVXPRINT</TD><TD>include the avx print function function</LI></TD></TR>
<TR>-<TD><LI>-DAVXMATH</TD><TD>include the avx math functions function</LI></TD></TR>
<TR>-<TD><LI>-DINFO</TD><TD>print info outside of the main loop</LI></TD></TR>
<TR>-<TD><LI>-DBENCH</TD><TD>include the benchmark function</LI></TD></TR>
<TR>-<TD><LI>-DDEBUG</TD><TD>whats going wrong, printing pointer address instead of value!!!</LI></TD></TR>
<TR>-<TD><LI>-DCOMPILE</TD><TD>compile ( recompile if compiler flag is present )</LI></TD></TR>
</UL>
</TABLE>
