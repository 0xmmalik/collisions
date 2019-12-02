<!-- pandoc -s -f gfm -t html README.md -o README.html -->

- [Prefixes](#prefixes)
  - [FastColl](#fastcoll)
  - [UniColl](#unicoll)
  - [HashClash CPC](#hashclash-cpc)


# Prefixes

Pre-computed prefixes mentioned in the workshop slides.

## FastColl

No prefix

<pre>$ radiff2 -x 01*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#4E9A06">0x00000000  </font>3775c1f1c4a75ae79ce0de7a5b108026 7u....Z....z[..&amp;   3775c1f1c4a75ae79ce0de7a5b108026 7u....Z....z[..&amp;
<font color="#CC0000">0x00000010! </font><font color="#4E9A06">02abd9</font><font color="#CC0000">39</font><font color="#4E9A06">c96c5f0212c27fdacd0da3b0</font> <font color="#4E9A06">...</font><font color="#CC0000">9</font><font color="#4E9A06">.l_.........</font>   <font color="#4E9A06">02abd9</font><font color="#CC0000">b9</font><font color="#4E9A06">c96c5f0212c27fdacd0da3b0</font> <font color="#4E9A06">...</font><font color="#CC0000">.</font><font color="#4E9A06">.l_.........</font>
<font color="#CC0000">0x00000020! </font><font color="#4E9A06">8cedfaf3e1a3fdb4ef09e7fbb1</font><font color="#CC0000">c399</font><font color="#4E9A06">1d</font> <font color="#4E9A06">.............</font><font color="#CC0000">..</font><font color="#4E9A06">.</font>   <font color="#4E9A06">8cedfaf3e1a3fdb4ef09e7fbb1</font><font color="#CC0000">439a</font><font color="#4E9A06">1d</font> <font color="#4E9A06">.............</font><font color="#CC0000">C.</font><font color="#4E9A06">.</font>
<font color="#CC0000">0x00000030! </font><font color="#4E9A06">cd91c845e66efd3dc7bb61</font><font color="#CC0000">52</font><font color="#4E9A06">3ef4e038</font> <font color="#4E9A06">...E.n.=..a</font><font color="#CC0000">R</font><font color="#4E9A06">&gt;..8</font>   <font color="#4E9A06">cd91c845e66efd3dc7bb61</font><font color="#CC0000">d2</font><font color="#4E9A06">3ef4e038</font> <font color="#4E9A06">...E.n.=..a</font><font color="#CC0000">.</font><font color="#4E9A06">&gt;..8</font>
<font color="#4E9A06">0x00000040  </font>49118569ebcc179c934f40eb3302ad20 I..i.....O@.3..    49118569ebcc179c934f40eb3302ad20 I..i.....O@.3.. 
<font color="#CC0000">0x00000050! </font><font color="#4E9A06">a4092d</font><font color="#CC0000">fb</font><font color="#4E9A06">15fa201dd1db17cddd29591e</font> <font color="#4E9A06">..-</font><font color="#CC0000">.</font><font color="#4E9A06">.. ......)Y.</font>   <font color="#4E9A06">a4092d</font><font color="#CC0000">7b</font><font color="#4E9A06">15fa201dd1db17cddd29591e</font> <font color="#4E9A06">..-</font><font color="#CC0000">{</font><font color="#4E9A06">.. ......)Y.</font>
<font color="#CC0000">0x00000060! </font><font color="#4E9A06">39899ef679469fe68b85c5efde</font><font color="#CC0000">424f</font><font color="#4E9A06">46</font> <font color="#4E9A06">9...yF.......</font><font color="#CC0000">BO</font><font color="#4E9A06">F</font>   <font color="#4E9A06">39899ef679469fe68b85c5efde</font><font color="#CC0000">c24e</font><font color="#4E9A06">46</font> <font color="#4E9A06">9...yF.......</font><font color="#CC0000">.N</font><font color="#4E9A06">F</font>
<font color="#CC0000">0x00000070! </font><font color="#4E9A06">c278759d8b65f450ea21c5</font><font color="#CC0000">59</font><font color="#4E9A06">1862ff7b</font> <font color="#4E9A06">.xu..e.P.!.</font><font color="#CC0000">Y</font><font color="#4E9A06">.b.{</font>   <font color="#4E9A06">c278759d8b65f450ea21c5</font><font color="#CC0000">d9</font><font color="#4E9A06">1862ff7b</font> <font color="#4E9A06">.xu..e.P.!.</font><font color="#CC0000">.</font><font color="#4E9A06">.b.{</font>
</pre>

No prefix, 2nd try.

<pre>
$ radiff2 -x 02*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#4E9A06">0x00000000  </font>1d9256c934f6c6f2c90c9790aa16552a ..V.4.........U*   1d9256c934f6c6f2c90c9790aa16552a ..V.4.........U*
<font color="#CC0000">0x00000010! </font><font color="#4E9A06">6800e7</font><font color="#CC0000">44</font><font color="#4E9A06">8c5639e847a680a64db02bf2</font> <font color="#4E9A06">h..</font><font color="#CC0000">D</font><font color="#4E9A06">.V9.G...M.+.</font>   <font color="#4E9A06">6800e7</font><font color="#CC0000">c4</font><font color="#4E9A06">8c5639e847a680a64db02bf2</font> <font color="#4E9A06">h..</font><font color="#CC0000">.</font><font color="#4E9A06">.V9.G...M.+.</font>
<font color="#CC0000">0x00000020! </font><font color="#4E9A06">f612d2e6d0ac132deffff0dc13</font><font color="#CC0000">10de</font><font color="#4E9A06">72</font> <font color="#4E9A06">.......-.....</font><font color="#CC0000">..</font><font color="#4E9A06">r</font>   <font color="#4E9A06">f612d2e6d0ac132deffff0dc13</font><font color="#CC0000">90dd</font><font color="#4E9A06">72</font> <font color="#4E9A06">.......-.....</font><font color="#CC0000">..</font><font color="#4E9A06">r</font>
<font color="#CC0000">0x00000030! </font><font color="#4E9A06">3299b0bbc765a666731056</font><font color="#CC0000">fc</font><font color="#4E9A06">9c5f458b</font> <font color="#4E9A06">2....e.fs.V</font><font color="#CC0000">.</font><font color="#4E9A06">._E.</font>   <font color="#4E9A06">3299b0bbc765a666731056</font><font color="#CC0000">7c</font><font color="#4E9A06">9c5f458b</font> <font color="#4E9A06">2....e.fs.V</font><font color="#CC0000">|</font><font color="#4E9A06">._E.</font>
<font color="#4E9A06">0x00000040  </font>6176c9563edf7e28dbabdc64b49a4400 av.V&gt;.~(...d..D.   6176c9563edf7e28dbabdc64b49a4400 av.V&gt;.~(...d..D.
<font color="#CC0000">0x00000050! </font><font color="#4E9A06">d34dbc</font><font color="#CC0000">1e</font><font color="#4E9A06">801cb238c9b340671a60a8c6</font> <font color="#4E9A06">.M.</font><font color="#CC0000">.</font><font color="#4E9A06">...8..@g.`..</font>   <font color="#4E9A06">d34dbc</font><font color="#CC0000">9e</font><font color="#4E9A06">801cb238c9b340671a60a8c6</font> <font color="#4E9A06">.M.</font><font color="#CC0000">.</font><font color="#4E9A06">...8..@g.`..</font>
<font color="#CC0000">0x00000060! </font><font color="#4E9A06">d3bb4808af043016b801105b92</font><font color="#CC0000">14</font><font color="#4E9A06">f91c</font> <font color="#4E9A06">..H...0....[.</font><font color="#CC0000">.</font><font color="#4E9A06">..</font>   <font color="#4E9A06">d3bb4808af043016b801105b92</font><font color="#CC0000">94</font><font color="#4E9A06">f91c</font> <font color="#4E9A06">..H...0....[.</font><font color="#CC0000">.</font><font color="#4E9A06">..</font>
<font color="#CC0000">0x00000070! </font><font color="#4E9A06">3d3cc6acff2cfdaddb2c2c</font><font color="#CC0000">4f</font><font color="#4E9A06">c1069b50</font> <font color="#4E9A06">=&lt;...,...,,</font><font color="#CC0000">O</font><font color="#4E9A06">...P</font>   <font color="#4E9A06">3d3cc6acff2cfdaddb2c2c</font><font color="#CC0000">cf</font><font color="#4E9A06">c1069b50</font> <font color="#4E9A06">=&lt;...,...,,</font><font color="#CC0000">.</font><font color="#4E9A06">...P</font>
</pre>

With a prefix.

<pre>
$ radiff2 -x 03*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#4E9A06">0x00000000  </font>4865726520697320612066696c652077 Here is a file w   4865726520697320612066696c652077 Here is a file w
<font color="#4E9A06">0x00000010  </font>69746820612066657720627974657300 ith a few bytes.   69746820612066657720627974657300 ith a few bytes.
...
<font color="#CC0000">0x00000050! </font><font color="#4E9A06">44179b</font><font color="#CC0000">f0</font><font color="#4E9A06">0ae0d26421e238e194180af6</font> <font color="#4E9A06">D..</font><font color="#CC0000">.</font><font color="#4E9A06">...d!.8.....</font>   <font color="#4E9A06">44179b</font><font color="#CC0000">70</font><font color="#4E9A06">0ae0d26421e238e194180af6</font> <font color="#4E9A06">D..</font><font color="#CC0000">p</font><font color="#4E9A06">...d!.8.....</font>
<font color="#CC0000">0x00000060! </font><font color="#4E9A06">93d2b5e4fc2f3a324f504601f1</font><font color="#CC0000">4bbf</font><font color="#4E9A06">02</font> <font color="#4E9A06">...../:2OPF..</font><font color="#CC0000">K.</font><font color="#4E9A06">.</font>   <font color="#4E9A06">93d2b5e4fc2f3a324f504601f1</font><font color="#CC0000">cbbe</font><font color="#4E9A06">02</font> <font color="#4E9A06">...../:2OPF..</font><font color="#CC0000">..</font><font color="#4E9A06">.</font>
<font color="#CC0000">0x00000070! </font><font color="#4E9A06">23eeefbf92b57c29d9c566</font><font color="#CC0000">08</font><font color="#4E9A06">315e7a1d</font> <font color="#4E9A06">#.....|)..f</font><font color="#CC0000">.</font><font color="#4E9A06">1^z.</font>   <font color="#4E9A06">23eeefbf92b57c29d9c566</font><font color="#CC0000">88</font><font color="#4E9A06">315e7a1d</font> <font color="#4E9A06">#.....|)..f</font><font color="#CC0000">.</font><font color="#4E9A06">1^z.</font>
<font color="#4E9A06">0x00000080  </font>2f5a9c5c128edff285175bdd67250578 /Z.\......[.g%.x   2f5a9c5c128edff285175bdd67250578 /Z.\......[.g%.x
<font color="#CC0000">0x00000090! </font><font color="#4E9A06">13f2bf</font><font color="#CC0000">d6</font><font color="#4E9A06">6459f2c88bc3006f8b5f88c6</font> <font color="#4E9A06">...</font><font color="#CC0000">.</font><font color="#4E9A06">dY.....o._..</font>   <font color="#4E9A06">13f2bf</font><font color="#CC0000">56</font><font color="#4E9A06">6459f2c88bc3006f8b5f88c6</font> <font color="#4E9A06">...</font><font color="#CC0000">V</font><font color="#4E9A06">dY.....o._..</font>
<font color="#CC0000">0x000000a0! </font><font color="#4E9A06">cb3d80e49f48915e3406d03a8b</font><font color="#CC0000">03</font><font color="#4E9A06">fbe0</font> <font color="#4E9A06">.=...H.^4..:.</font><font color="#CC0000">.</font><font color="#4E9A06">..</font>   <font color="#4E9A06">cb3d80e49f48915e3406d03a8b</font><font color="#CC0000">83</font><font color="#4E9A06">fbe0</font> <font color="#4E9A06">.=...H.^4..:.</font><font color="#CC0000">.</font><font color="#4E9A06">..</font>
<font color="#CC0000">0x000000b0! </font><font color="#4E9A06">ed18670fc83ac9a1e748f6</font><font color="#CC0000">2a</font><font color="#4E9A06">d25c30c0</font> <font color="#4E9A06">..g..:...H.</font><font color="#CC0000">*</font><font color="#4E9A06">.\0.</font>   <font color="#4E9A06">ed18670fc83ac9a1e748f6</font><font color="#CC0000">aa</font><font color="#4E9A06">d25c30c0</font> <font color="#4E9A06">..g..:...H.</font><font color="#CC0000">.</font><font color="#4E9A06">.\0.</font>
</pre>


## UniColl

Default `N=1` variant.

<pre>
$ radiff2 -x 04*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#CC0000">0x00000000! </font><font color="#4E9A06">48657265206973206d</font><font color="#CC0000">79</font><font color="#4E9A06">207072656669</font> <font color="#4E9A06">Here is m</font><font color="#CC0000">y</font><font color="#4E9A06"> prefi</font>   <font color="#4E9A06">48657265206973206d</font><font color="#CC0000">7a</font><font color="#4E9A06">207072656669</font> <font color="#4E9A06">Here is m</font><font color="#CC0000">z</font><font color="#4E9A06"> prefi</font>
<font color="#4E9A06">0x00000010  </font>7821210a853377e34e2db4f73352cd17 x!!..3w.N-..3R..   7821210a853377e34e2db4f73352cd17 x!!..3w.N-..3R..
<font color="#4E9A06">0x00000020  </font>63f024118e42ee0d6d731d18faba3f2d c.$..B..ms....?-   63f024118e42ee0d6d731d18faba3f2d c.$..B..ms....?-
...
<font color="#CC0000">0x00000040! </font><font color="#4E9A06">537543d73b339afee7</font><font color="#CC0000">b8</font><font color="#4E9A06">edbdaea807b9</font> <font color="#4E9A06">SuC.;3...</font><font color="#CC0000">.</font><font color="#4E9A06">......</font>   <font color="#4E9A06">537543d73b339afee7</font><font color="#CC0000">b7</font><font color="#4E9A06">edbdaea807b9</font> <font color="#4E9A06">SuC.;3...</font><font color="#CC0000">.</font><font color="#4E9A06">......</font>
<font color="#4E9A06">0x00000050  </font>f449fa94340154dbbe873c39afcda182 .I..4.T...&lt;9....   f449fa94340154dbbe873c39afcda182 .I..4.T...&lt;9....
<font color="#4E9A06">0x00000060  </font>c4ea3af89b7cbad3acaf3d47a1030d34 ..:..|....=G...4   c4ea3af89b7cbad3acaf3d47a1030d34 ..:..|....=G...4
...
</pre>

`N = 2` variant.

<pre>
$ radiff2 -x 05-uc-n2-*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#CC0000">0x00000000! </font><font color="#4E9A06">556e69</font><font color="#CC0000">43</font><font color="#4E9A06">6f6c6c203220707265666978</font> <font color="#4E9A06">Uni</font><font color="#CC0000">C</font><font color="#4E9A06">oll 2 prefix</font>   <font color="#4E9A06">556e69</font><font color="#CC0000">c3</font><font color="#4E9A06">6f6c6c203220707265666978</font> <font color="#4E9A06">Uni</font><font color="#CC0000">.</font><font color="#4E9A06">oll 2 prefix</font>
<font color="#CC0000">0x00000010! </font><font color="#4E9A06">2032306224fa3f502f7ab1</font><font color="#CC0000">a7</font><font color="#4E9A06">04dc2f39</font> <font color="#4E9A06"> 20b$.?P/z.</font><font color="#CC0000">.</font><font color="#4E9A06">../9</font>   <font color="#4E9A06">2032306224fa3f502f7ab1</font><font color="#CC0000">27</font><font color="#4E9A06">04dc2f39</font> <font color="#4E9A06"> 20b$.?P/z.</font><font color="#CC0000">&apos;</font><font color="#4E9A06">../9</font>
<font color="#4E9A06">0x00000020  </font>07e76f33b46497ddb1958ef3cb6018b1 ..o3.d.......`..   07e76f33b46497ddb1958ef3cb6018b1 ..o3.d.......`..
<font color="#CC0000">0x00000030! </font><font color="#4E9A06">9fe9dcb3d803fc</font><font color="#CC0000">7c</font><font color="#4E9A06">52408e36af0c86c7</font> <font color="#4E9A06">.......</font><font color="#CC0000">|</font><font color="#4E9A06">R@.6....</font>   <font color="#4E9A06">9fe9dcb3d803fc</font><font color="#CC0000">84</font><font color="#4E9A06">52408e36af0c86c7</font> <font color="#4E9A06">.......</font><font color="#CC0000">.</font><font color="#4E9A06">R@.6....</font>
<font color="#CC0000">0x00000040! </font><font color="#4E9A06">8c4162</font><font color="#CC0000">73</font><font color="#4E9A06">c9b9a7eb031068f05b8249ee</font> <font color="#4E9A06">.Ab</font><font color="#CC0000">s</font><font color="#4E9A06">......h.[.I.</font>   <font color="#4E9A06">8c4162</font><font color="#CC0000">f3</font><font color="#4E9A06">c9b9a7eb031068f05b8249ee</font> <font color="#4E9A06">.Ab</font><font color="#CC0000">.</font><font color="#4E9A06">......h.[.I.</font>
<font color="#CC0000">0x00000050! </font><font color="#4E9A06">b677d550e2b8d7a2611678</font><font color="#CC0000">b0</font><font color="#4E9A06">35241b2f</font> <font color="#4E9A06">.w.P....a.x</font><font color="#CC0000">.</font><font color="#4E9A06">5$./</font>   <font color="#4E9A06">b677d550e2b8d7a2611678</font><font color="#CC0000">30</font><font color="#4E9A06">35241b2f</font> <font color="#4E9A06">.w.P....a.x</font><font color="#CC0000">0</font><font color="#4E9A06">5$./</font>
<font color="#4E9A06">0x00000060  </font>5a83e2e0494fb70d7d7ce73fccb7f372 Z...IO..}|.?...r   5a83e2e0494fb70d7d7ce73fccb7f372 Z...IO..}|.?...r
<font color="#CC0000">0x00000070! </font><font color="#4E9A06">8a5571a0b2346c</font><font color="#CC0000">0e</font><font color="#4E9A06">45ee0460ed3362bc</font> <font color="#4E9A06">.Uq..4l</font><font color="#CC0000">.</font><font color="#4E9A06">E..`.3b.</font>   <font color="#4E9A06">8a5571a0b2346c</font><font color="#CC0000">06</font><font color="#4E9A06">45ee0460ed3362bc</font> <font color="#4E9A06">.Uq..4l</font><font color="#CC0000">.</font><font color="#4E9A06">E..`.3b.</font>
</pre>


`N = 3` variant.

<pre>
$ radiff2 -x 05-uc-n3-*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#4E9A06">0x00000000  </font>556e69436f6c6c203320707265666978 UniColl 3 prefix   556e69436f6c6c203320707265666978 UniColl 3 prefix
<font color="#CC0000">0x00000010! </font><font color="#4E9A06">20323062ecd20c562f</font><font color="#CC0000">03</font><font color="#4E9A06">f666d1768f87</font> <font color="#4E9A06"> 20b...V/</font><font color="#CC0000">.</font><font color="#4E9A06">.f.v..</font>   <font color="#4E9A06">20323062ecd20c562f</font><font color="#CC0000">04</font><font color="#4E9A06">f666d1768f87</font> <font color="#4E9A06"> 20b...V/</font><font color="#CC0000">.</font><font color="#4E9A06">.f.v..</font>
<font color="#CC0000">0x00000020! </font><font color="#4E9A06">ffe47becf3310a</font><font color="#CC0000">65</font><font color="#4E9A06">66b5bd6df52bfd1e</font> <font color="#4E9A06">..{..1.</font><font color="#CC0000">e</font><font color="#4E9A06">f..m.+..</font>   <font color="#4E9A06">ffe47becf3310a</font><font color="#CC0000">e5</font><font color="#4E9A06">66b5bd6df52bfd1e</font> <font color="#4E9A06">..{..1.</font><font color="#CC0000">.</font><font color="#4E9A06">f..m.+..</font>
<font color="#CC0000">0x00000030! </font><font color="#4E9A06">4d2d99370cb61bd56394dc2edb97f2</font><font color="#CC0000">10</font> <font color="#4E9A06">M-.7....c......</font><font color="#CC0000">.</font>   <font color="#4E9A06">4d2d99370cb61bd56394dc2edb97f2</font><font color="#CC0000">90</font> <font color="#4E9A06">M-.7....c......</font><font color="#CC0000">.</font>
<font color="#4E9A06">0x00000040  </font>22ba25c4f6f7ecc6d70edb5d18df90f9 &quot;.%........]....   22ba25c4f6f7ecc6d70edb5d18df90f9 &quot;.%........]....
<font color="#CC0000">0x00000050! </font><font color="#4E9A06">6ac52a0acc883c7f6c</font><font color="#CC0000">ae</font><font color="#4E9A06">2471f9bf7617</font> <font color="#4E9A06">j.*...&lt;.l</font><font color="#CC0000">.</font><font color="#4E9A06">$q..v.</font>   <font color="#4E9A06">6ac52a0acc883c7f6c</font><font color="#CC0000">ad</font><font color="#4E9A06">2471f9bf7617</font> <font color="#4E9A06">j.*...&lt;.l</font><font color="#CC0000">.</font><font color="#4E9A06">$q..v.</font>
<font color="#CC0000">0x00000060! </font><font color="#4E9A06">be60aade6f0b11</font><font color="#CC0000">d0</font><font color="#4E9A06">52e20e85bb0b8b76</font> <font color="#4E9A06">.`..o..</font><font color="#CC0000">.</font><font color="#4E9A06">R......v</font>   <font color="#4E9A06">be60aade6f0b11</font><font color="#CC0000">50</font><font color="#4E9A06">52e20e85bb0b8b76</font> <font color="#4E9A06">.`..o..</font><font color="#CC0000">P</font><font color="#4E9A06">R......v</font>
<font color="#CC0000">0x00000070! </font><font color="#4E9A06">a1188703d29d39807910503fbc1765</font><font color="#CC0000">01</font> <font color="#4E9A06">......9.y.P?..e</font><font color="#CC0000">.</font>   <font color="#4E9A06">a1188703d29d39807910503fbc1765</font><font color="#CC0000">81</font> <font color="#4E9A06">......9.y.P?..e</font><font color="#CC0000">.</font>
</pre>

Prefix longer than a block.

<pre>
$ radiff2 -x 06*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#4E9A06">0x00000000  </font>000102030405060708090a0b0c0d0e0f ................   000102030405060708090a0b0c0d0e0f ................
<font color="#4E9A06">0x00000010  </font>101112131415161718191a1b1c1d1e1f ................   101112131415161718191a1b1c1d1e1f ................
...
<font color="#CC0000">0x00000040! </font><font color="#4E9A06">68657265206973206d</font><font color="#CC0000">79</font><font color="#4E9A06">207072656669</font> <font color="#4E9A06">here is m</font><font color="#CC0000">y</font><font color="#4E9A06"> prefi</font>   <font color="#4E9A06">68657265206973206d</font><font color="#CC0000">7a</font><font color="#4E9A06">207072656669</font> <font color="#4E9A06">here is m</font><font color="#CC0000">z</font><font color="#4E9A06"> prefi</font>
<font color="#4E9A06">0x00000050  </font>7821210aa48ed83fae42a56b47e1b472 x!!....?.B.kG..r   7821210aa48ed83fae42a56b47e1b472 x!!....?.B.kG..r
<font color="#4E9A06">0x00000060  </font>7a862796603ae69a8a377d2f8eaca6ad z.&apos;.`:...7}/....   7a862796603ae69a8a377d2f8eaca6ad z.&apos;.`:...7}/....
...
<font color="#CC0000">0x00000080! </font><font color="#4E9A06">39f9b5e5d8a6c40289</font><font color="#CC0000">df</font><font color="#4E9A06">e2c0821ef8fa</font> <font color="#4E9A06">9........</font><font color="#CC0000">.</font><font color="#4E9A06">......</font>   <font color="#4E9A06">39f9b5e5d8a6c40289</font><font color="#CC0000">de</font><font color="#4E9A06">e2c0821ef8fa</font> <font color="#4E9A06">9........</font><font color="#CC0000">.</font><font color="#4E9A06">......</font>
<font color="#4E9A06">0x00000090  </font>1ec3c43e77171298d678ed80dc4f8386 ...&gt;w....x...O..   1ec3c43e77171298d678ed80dc4f8386 ...&gt;w....x...O..
<font color="#4E9A06">0x000000a0  </font>21687744e2dc81c86933eb953a6008a0 !hwD....i3..:`..   21687744e2dc81c86933eb953a6008a0 !hwD....i3..:`..
...
</pre>


20 bytes prefix in the last block.

<pre>
$ radiff2 -x 07*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#CC0000">0x00000000! </font><font color="#4E9A06">48657265206973206d</font><font color="#CC0000">79</font><font color="#4E9A06">206c6f6e6720</font> <font color="#4E9A06">Here is m</font><font color="#CC0000">y</font><font color="#4E9A06"> long </font>   <font color="#4E9A06">48657265206973206d</font><font color="#CC0000">7a</font><font color="#4E9A06">206c6f6e6720</font> <font color="#4E9A06">Here is m</font><font color="#CC0000">z</font><font color="#4E9A06"> long </font>
<font color="#4E9A06">0x00000010  </font>707265666978210a17ef033a3b0bd8ba prefix!....:;...   707265666978210a17ef033a3b0bd8ba prefix!....:;...
<font color="#4E9A06">0x00000020  </font>110c27fe718cec39ab4897fb818e7a50 ..&apos;.q..9.H....zP   110c27fe718cec39ab4897fb818e7a50 ..&apos;.q..9.H....zP
...
<font color="#CC0000">0x00000040! </font><font color="#4E9A06">70f46604c82316b083</font><font color="#CC0000">99</font><font color="#4E9A06">e576099213f0</font> <font color="#4E9A06">p.f..#...</font><font color="#CC0000">.</font><font color="#4E9A06">.v....</font>   <font color="#4E9A06">70f46604c82316b083</font><font color="#CC0000">98</font><font color="#4E9A06">e576099213f0</font> <font color="#4E9A06">p.f..#...</font><font color="#CC0000">.</font><font color="#4E9A06">.v....</font>
<font color="#4E9A06">0x00000050  </font>3e3ed2bbd9fb3e007864b489af98fbbd &gt;&gt;....&gt;.xd......   3e3ed2bbd9fb3e007864b489af98fbbd &gt;&gt;....&gt;.xd......
<font color="#4E9A06">0x00000060  </font>aae1036b7761463b84d425a73b00091a ...kwaF;..%.;...   aae1036b7761463b84d425a73b00091a ...kwaF;..%.;...
...
</pre>

24 bytes prefix in the last block.

<pre>
$ radiff2 -x 08*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#CC0000">0x00000000! </font><font color="#4E9A06">48657265206973206d</font><font color="#CC0000">79</font><font color="#4E9A06">206c6f6e6720</font> <font color="#4E9A06">Here is m</font><font color="#CC0000">y</font><font color="#4E9A06"> long </font>   <font color="#4E9A06">48657265206973206d</font><font color="#CC0000">7a</font><font color="#4E9A06">206c6f6e6720</font> <font color="#4E9A06">Here is m</font><font color="#CC0000">z</font><font color="#4E9A06"> long </font>
<font color="#4E9A06">0x00000010  </font>70726566697821303132330aa54d0aa2 prefix!0123..M..   70726566697821303132330aa54d0aa2 prefix!0123..M..
<font color="#4E9A06">0x00000020  </font>4a9e0eb120bcdf89bfedd3ebbbe2e96f J... ..........o   4a9e0eb120bcdf89bfedd3ebbbe2e96f J... ..........o
...
<font color="#CC0000">0x00000040! </font><font color="#4E9A06">b47ae4de0027f8c7ad</font><font color="#CC0000">ef</font><font color="#4E9A06">b12d2535f79f</font> <font color="#4E9A06">.z...&apos;...</font><font color="#CC0000">.</font><font color="#4E9A06">.-%5..</font>   <font color="#4E9A06">b47ae4de0027f8c7ad</font><font color="#CC0000">ee</font><font color="#4E9A06">b12d2535f79f</font> <font color="#4E9A06">.z...&apos;...</font><font color="#CC0000">.</font><font color="#4E9A06">.-%5..</font>
<font color="#4E9A06">0x00000050  </font>fa01643c068a5b66ad46fa5f11ea91c6 ..d&lt;..[f.F._....   fa01643c068a5b66ad46fa5f11ea91c6 ..d&lt;..[f.F._....
<font color="#4E9A06">0x00000060  </font>d370114557dd8a0fb8af4d0dd2d24043 .p.EW.....M...@C   d370114557dd8a0fb8af4d0dd2d24043 .p.EW.....M...@C
...
</pre>

PNG exploit prefix.

<pre>
$ radiff2 -x 09*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#4E9A06">0x00000000  </font>89504e470d0a1a0a00000033614c4947 .PNG.......3aLIG   89504e470d0a1a0a00000033614c4947 .PNG.......3aLIG
<font color="#4E9A06">0x00000010  </font>00000000000000000000000000000000 ................   00000000000000000000000000000000 ................
...
<font color="#CC0000">0x00000040! </font><font color="#4E9A06">000000000000000000</font><font color="#CC0000">00</font><font color="#4E9A06">71634f4c4c21</font> <font color="#4E9A06">.........</font><font color="#CC0000">.</font><font color="#4E9A06">qcOLL!</font>   <font color="#4E9A06">000000000000000000</font><font color="#CC0000">01</font><font color="#4E9A06">71634f4c4c21</font> <font color="#4E9A06">.........</font><font color="#CC0000">.</font><font color="#4E9A06">qcOLL!</font>
<font color="#4E9A06">0x00000050  </font>a0b85e62bd937ae3f7f3b62d89ffc608 ..^b..z....-....   a0b85e62bd937ae3f7f3b62d89ffc608 ..^b..z....-....
<font color="#4E9A06">0x00000060  </font>951b5d7521891436c69bb8505ffea921 ..]u!..6...P_..!   951b5d7521891436c69bb8505ffea921 ..]u!..6...P_..!
...
<font color="#CC0000">0x00000080! </font><font color="#4E9A06">339685034dc455c5ef</font><font color="#CC0000">1f</font><font color="#4E9A06">472c0453abb0</font> <font color="#4E9A06">3...M.U..</font><font color="#CC0000">.</font><font color="#4E9A06">G,.S..</font>   <font color="#4E9A06">339685034dc455c5ef</font><font color="#CC0000">1e</font><font color="#4E9A06">472c0453abb0</font> <font color="#4E9A06">3...M.U..</font><font color="#CC0000">.</font><font color="#4E9A06">G,.S..</font>
<font color="#4E9A06">0x00000090  </font>10c1a7845fc28bdc68e914a123b9bfb4 ...._...h...#...   10c1a7845fc28bdc68e914a123b9bfb4 ...._...h...#...
<font color="#4E9A06">0x000000a0  </font>85f495d5d788147c24a1c1fce1ad57b1 .......|$.....W.   85f495d5d788147c24a1c1fce1ad57b1 .......|$.....W.
...
</pre>

## HashClash CPC


yes/no

<pre>
$ radiff2 -x 10*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#CC0000">0x00000000! 6e6f00</font><font color="#4E9A06">00000000000000000000000000</font> <font color="#CC0000">no.</font><font color="#4E9A06">.............</font>   <font color="#CC0000">796573</font><font color="#4E9A06">00000000000000000000000000</font> <font color="#CC0000">yes</font><font color="#4E9A06">.............</font>
<font color="#4E9A06">0x00000010  </font>00000000000000000000000000000000 ................   00000000000000000000000000000000 ................
<font color="#4E9A06">0x00000020  </font>00000000000000000000000000000000 ................   00000000000000000000000000000000 ................
<font color="#CC0000">0x00000030! </font><font color="#4E9A06">0000000000000000</font><font color="#CC0000">1971e7f70972fb06</font> <font color="#4E9A06">........</font><font color="#CC0000">.q...r..</font>   <font color="#4E9A06">0000000000000000</font><font color="#CC0000">b74638098a46f17b</font> <font color="#4E9A06">........</font><font color="#CC0000">.F8..F.{</font>
<font color="#4E9A06">0x00000040  </font>f34526136660c801b92a75255a6723a6 .E&amp;.f`...*u%Zg#.   f34526136660c801b92a75255a6723a6 .E&amp;.f`...*u%Zg#.
<font color="#4E9A06">0x00000050  </font>923deb8db0b757f1459f2295bec04375 .=....W.E.&quot;...Cu   923deb8db0b757f1459f2295bec04375 .=....W.E.&quot;...Cu
<font color="#CC0000">0x00000060! </font><font color="#4E9A06">9198a2d3e0fd59edd1c5fa0b796597</font><font color="#CC0000">51</font> <font color="#4E9A06">......Y.....ye.</font><font color="#CC0000">Q</font>   <font color="#4E9A06">9198a2d3e0fd59edd1c5fa0b796597</font><font color="#CC0000">4d</font> <font color="#4E9A06">......Y.....ye.</font><font color="#CC0000">M</font>
<font color="#4E9A06">0x00000070  </font>b3b3e40c110c9032de4ba14bb81b5ec8 .......2.K.K..^.   b3b3e40c110c9032de4ba14bb81b5ec8 .......2.K.K..^.
<font color="#4E9A06">0x00000080  </font>25d38f19cd104307d9bbff8cb75a23f9 %.....C......Z#.   25d38f19cd104307d9bbff8cb75a23f9 %.....C......Z#.
...
<font color="#CC0000">0x000000a0! </font><font color="#4E9A06">ba784000c37e93b231a36e2d34</font><font color="#CC0000">72</font><font color="#4E9A06">4ac9</font> <font color="#4E9A06">.x@..~..1.n-4</font><font color="#CC0000">r</font><font color="#4E9A06">J.</font>   <font color="#4E9A06">ba784000c37e93b231a36e2d34</font><font color="#CC0000">6a</font><font color="#4E9A06">4ac9</font> <font color="#4E9A06">.x@..~..1.n-4</font><font color="#CC0000">j</font><font color="#4E9A06">J.</font>
<font color="#4E9A06">0x000000b0  </font>534ec045361ec86a5698e6f0571d6198 SN.E6..jV...W.a.   534ec045361ec86a5698e6f0571d6198 SN.E6..jV...W.a.
<font color="#4E9A06">0x000000c0  </font>13fcffcd4d83a2d2bbb8dc042be2b883 ....M.......+...   13fcffcd4d83a2d2bbb8dc042be2b883 ....M.......+...
...
<font color="#CC0000">0x000000e0! </font><font color="#4E9A06">7d86e4351eb833eeea15d181</font><font color="#CC0000">fa</font><font color="#4E9A06">9662ec</font> <font color="#4E9A06">}..5..3.....</font><font color="#CC0000">.</font><font color="#4E9A06">.b.</font>   <font color="#4E9A06">7d86e4351eb833eeea15d181</font><font color="#CC0000">ba</font><font color="#4E9A06">9662ec</font> <font color="#4E9A06">}..5..3.....</font><font color="#CC0000">.</font><font color="#4E9A06">.b.</font>
<font color="#4E9A06">0x000000f0  </font>7531fbda4fae246f67d6af109629fbc7 u1..O.$og....)..   7531fbda4fae246f67d6af109629fbc7 u1..O.$og....)..
<font color="#4E9A06">0x00000100  </font>a332bba9ead5e4ae1fc2fb234122b2e0 .2.........#A&quot;..   a332bba9ead5e4ae1fc2fb234122b2e0 .2.........#A&quot;..
...
<font color="#CC0000">0x00000120! </font><font color="#4E9A06">8bc95c93a5efa4227d9a66516eed</font><font color="#CC0000">af</font><font color="#4E9A06">70</font> <font color="#4E9A06">..\....&quot;}.fQn.</font><font color="#CC0000">.</font><font color="#4E9A06">p</font>   <font color="#4E9A06">8bc95c93a5efa4227d9a66516eed</font><font color="#CC0000">ad</font><font color="#4E9A06">70</font> <font color="#4E9A06">..\....&quot;}.fQn.</font><font color="#CC0000">.</font><font color="#4E9A06">p</font>
<font color="#4E9A06">0x00000130  </font>3290d4bd6792389bdc150dbfdc717227 2...g.8......qr&apos;   3290d4bd6792389bdc150dbfdc717227 2...g.8......qr&apos;
<font color="#4E9A06">0x00000140  </font>e05b43fa4459e860f7637ff0730ad4be .[C.DY.`.c..s...   e05b43fa4459e860f7637ff0730ad4be .[C.DY.`.c..s...
...
<font color="#CC0000">0x00000160! </font><font color="#4E9A06">e860db910013c91d7a619b9a5d</font><font color="#CC0000">60</font><font color="#4E9A06">bd71</font> <font color="#4E9A06">.`......za..]</font><font color="#CC0000">`</font><font color="#4E9A06">.q</font>   <font color="#4E9A06">e860db910013c91d7a619b9a5d</font><font color="#CC0000">5e</font><font color="#4E9A06">bd71</font> <font color="#4E9A06">.`......za..]</font><font color="#CC0000">^</font><font color="#4E9A06">.q</font>
<font color="#4E9A06">0x00000170  </font>231ad2bda6e038660b8cf599567963d6 #.....8f....Vyc.   231ad2bda6e038660b8cf599567963d6 #.....8f....Vyc.
<font color="#4E9A06">0x00000180  </font>6e5ed77ec34e9d5f6523c038c9555aa1 n^.~.N._e#.8.UZ.   6e5ed77ec34e9d5f6523c038c9555aa1 n^.~.N._e#.8.UZ.
...
<font color="#CC0000">0x000001a0! </font><font color="#4E9A06">0260f662913470fec334546d7607</font><font color="#CC0000">ff</font><font color="#4E9A06">1a</font> <font color="#4E9A06">.`.b.4p..4Tmv.</font><font color="#CC0000">.</font><font color="#4E9A06">.</font>   <font color="#4E9A06">0260f662913470fec334546d7607</font><font color="#CC0000">7f</font><font color="#4E9A06">1a</font> <font color="#4E9A06">.`.b.4p..4Tmv.</font><font color="#CC0000">.</font><font color="#4E9A06">.</font>
<font color="#4E9A06">0x000001b0  </font>7353e60b08fb8280ad5f22151869b56e sS......._&quot;..i.n   7353e60b08fb8280ad5f22151869b56e sS......._&quot;..i.n
<font color="#4E9A06">0x000001c0  </font>bb06c3a7ff391552befed45cd2555a71 .....9.R...\.UZq   bb06c3a7ff391552befed45cd2555a71 .....9.R...\.UZq
...
<font color="#CC0000">0x000001e0! </font><font color="#4E9A06">1f8a9ad842bf6c016a392684</font><font color="#CC0000">6c</font><font color="#4E9A06">58e2e4</font> <font color="#4E9A06">....B.l.j9&amp;.</font><font color="#CC0000">l</font><font color="#4E9A06">X..</font>   <font color="#4E9A06">1f8a9ad842bf6c016a392684</font><font color="#CC0000">74</font><font color="#4E9A06">58e2e4</font> <font color="#4E9A06">....B.l.j9&amp;.</font><font color="#CC0000">t</font><font color="#4E9A06">X..</font>
<font color="#4E9A06">0x000001f0  </font>00d4677b27bd936ddff0104a2b007e68 ..g{&apos;..m...J+.~h   00d4677b27bd936ddff0104a2b007e68 ..g{&apos;..m...J+.~h
<font color="#4E9A06">0x00000200  </font>1dded58a6789ea520c32bd30a28cbed0 ....g..R.2.0....   1dded58a6789ea520c32bd30a28cbed0 ....g..R.2.0....
...
<font color="#CC0000">0x00000220! </font><font color="#4E9A06">e6186ee3f052e435836142357297</font><font color="#CC0000">cd</font><font color="#4E9A06">8d</font> <font color="#4E9A06">..n..R.5.aB5r.</font><font color="#CC0000">.</font><font color="#4E9A06">.</font>   <font color="#4E9A06">e6186ee3f052e435836142357297</font><font color="#CC0000">c5</font><font color="#4E9A06">8d</font> <font color="#4E9A06">..n..R.5.aB5r.</font><font color="#CC0000">.</font><font color="#4E9A06">.</font>
<font color="#4E9A06">0x00000230  </font>4ff793685a705f5a043ad542c1fa0fe2 O..hZp_Z.:.B....   4ff793685a705f5a043ad542c1fa0fe2 O..hZp_Z.:.B....
<font color="#4E9A06">0x00000240  </font>ae57dbaff151b8b73818ef2eb8a6a92c .W...Q..8......,   ae57dbaff151b8b73818ef2eb8a6a92c .W...Q..8......,
...
<font color="#CC0000">0x00000260! </font><font color="#4E9A06">4f9cfa623d4246596732ec99da897a</font><font color="#CC0000">08</font> <font color="#4E9A06">O..b=BFYg2....z</font><font color="#CC0000">.</font>   <font color="#4E9A06">4f9cfa623d4246596732ec99da897a</font><font color="#CC0000">88</font> <font color="#4E9A06">O..b=BFYg2....z</font><font color="#CC0000">.</font>
<font color="#4E9A06">0x00000270  </font>e7ade321ed3c4bc04d9f833cdc7fb70a ...!.&lt;K.M..&lt;....   e7ade321ed3c4bc04d9f833cdc7fb70a ...!.&lt;K.M..&lt;....
</pre>

Colliding PE headers (CPC+IPC exploit).

<pre>
$ radiff2 -x 11*
  offset     0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF    0 1 2 3 4 5 6 7 8 9 A B C D E F 0123456789ABCDEF
<font color="#4E9A06">0x00000000  </font>4d5a90000300000004000000ffff0000 MZ..............   4d5a90000300000004000000ffff0000 MZ..............
<font color="#4E9A06">0x00000010  </font>b8000000000000004000000000000000 ........@.......   b8000000000000004000000000000000 ........@.......
...
<font color="#CC0000">0x00000030! </font><font color="#4E9A06">000000000000000000000000</font><font color="#CC0000">8004</font><font color="#4E9A06">0000</font> <font color="#4E9A06">............</font><font color="#CC0000">..</font><font color="#4E9A06">..</font>   <font color="#4E9A06">000000000000000000000000</font><font color="#CC0000">c002</font><font color="#4E9A06">0000</font> <font color="#4E9A06">............</font><font color="#CC0000">..</font><font color="#4E9A06">..</font>
<font color="#CC0000">0x00000040! </font><font color="#4E9A06">2f</font><font color="#CC0000">3d2d3d2d3d2d3d2d3d2d3d2d3d2d</font><font color="#4E9A06">5c</font> <font color="#4E9A06">/</font><font color="#CC0000">=-=-=-=-=-=-=-</font><font color="#4E9A06">\</font>   <font color="#4E9A06">2f</font><font color="#CC0000">2d3d2d3d2d3d2d3d2d3d2d3d2d3d</font><font color="#4E9A06">5c</font> <font color="#4E9A06">/</font><font color="#CC0000">-=-=-=-=-=-=-=</font><font color="#4E9A06">\</font>
<font color="#CC0000">0x00000050! </font><font color="#4E9A06">7c</font><font color="#CC0000">5045204350432048656164657200</font><font color="#4E9A06">7c</font> <font color="#4E9A06">|</font><font color="#CC0000">PE CPC Header.</font><font color="#4E9A06">|</font>   <font color="#4E9A06">7c</font><font color="#CC0000">0050452043504320686561646572</font><font color="#4E9A06">7c</font> <font color="#4E9A06">|</font><font color="#CC0000">.PE CPC header</font><font color="#4E9A06">|</font>
<font color="#CC0000">0x00000060! </font><font color="#4E9A06">5c</font><font color="#CC0000">2d3d2d3d2d3d2d3d2d3d2d3d2d3d</font><font color="#4E9A06">2f</font> <font color="#4E9A06">\</font><font color="#CC0000">-=-=-=-=-=-=-=</font><font color="#4E9A06">/</font>   <font color="#4E9A06">5c</font><font color="#CC0000">3d2d3d2d3d2d3d2d3d2d3d2d3d2d</font><font color="#4E9A06">2f</font> <font color="#4E9A06">\</font><font color="#CC0000">=-=-=-=-=-=-=-</font><font color="#4E9A06">/</font>
<font color="#CC0000">0x00000070! 416e6765</font><font color="#4E9A06">00000000</font><font color="#CC0000">509f71323d4975dd</font> <font color="#CC0000">Ange</font><font color="#4E9A06">....</font><font color="#CC0000">P.q2=Iu.</font>   <font color="#CC0000">4d617263</font><font color="#4E9A06">00000000</font><font color="#CC0000">9fcb1d973ffdc538</font> <font color="#CC0000">Marc</font><font color="#4E9A06">....</font><font color="#CC0000">....?..8</font>
<font color="#4E9A06">0x00000080  </font>e34520db90d9f91a1e3255d14dc914f6 .E ......2U.M...   e34520db90d9f91a1e3255d14dc914f6 .E ......2U.M...
<font color="#4E9A06">0x00000090  </font>add979c83ed7223defab83e8ddcb87f0 ..y.&gt;.&quot;=........   add979c83ed7223defab83e8ddcb87f0 ..y.&gt;.&quot;=........
<font color="#CC0000">0x000000a0! </font><font color="#4E9A06">9fe407a66723d8f326eab0d2d82c38</font><font color="#CC0000">03</font> <font color="#4E9A06">....g#..&amp;....,8</font><font color="#CC0000">.</font>   <font color="#4E9A06">9fe407a66723d8f326eab0d2d82c38</font><font color="#CC0000">02</font> <font color="#4E9A06">....g#..&amp;....,8</font><font color="#CC0000">.</font>
<font color="#4E9A06">0x000000b0  </font>fad007207bef85df02aa38f21a2744ab ... {.....8..&apos;D.   fad007207bef85df02aa38f21a2744ab ... {.....8..&apos;D.
<font color="#4E9A06">0x000000c0  </font>923f06839e57468babe99519a2645eeb .?...WF......d^.   923f06839e57468babe99519a2645eeb .?...WF......d^.
...
<font color="#CC0000">0x000000e0! </font><font color="#4E9A06">ee6b961a78ee511151af743712d0</font><font color="#CC0000">9c</font><font color="#4E9A06">78</font> <font color="#4E9A06">.k..x.Q.Q.t7..</font><font color="#CC0000">.</font><font color="#4E9A06">x</font>   <font color="#4E9A06">ee6b961a78ee511151af743712d0</font><font color="#CC0000">9a</font><font color="#4E9A06">78</font> <font color="#4E9A06">.k..x.Q.Q.t7..</font><font color="#CC0000">.</font><font color="#4E9A06">x</font>
<font color="#4E9A06">0x000000f0  </font>bf5b5056d2fda374e6176a4b8ae733d9 .[PV...t..jK..3.   bf5b5056d2fda374e6176a4b8ae733d9 .[PV...t..jK..3.
<font color="#4E9A06">0x00000100  </font>c326a674f0d4e9f95dd2e7b4a8fb920a .&amp;.t....].......   c326a674f0d4e9f95dd2e7b4a8fb920a .&amp;.t....].......
...
<font color="#CC0000">0x00000120! </font><font color="#4E9A06">cd7ac5a953cf30028fe9680f3253</font><font color="#CC0000">9e</font><font color="#4E9A06">d2</font> <font color="#4E9A06">.z..S.0...h.2S</font><font color="#CC0000">.</font><font color="#4E9A06">.</font>   <font color="#4E9A06">cd7ac5a953cf30028fe9680f3253</font><font color="#CC0000">8e</font><font color="#4E9A06">d2</font> <font color="#4E9A06">.z..S.0...h.2S</font><font color="#CC0000">.</font><font color="#4E9A06">.</font>
<font color="#4E9A06">0x00000130  </font>15e45262c9ecb8ae0f7b39957b266b53 ..Rb.....{9.{&amp;kS   15e45262c9ecb8ae0f7b39957b266b53 ..Rb.....{9.{&amp;kS
<font color="#4E9A06">0x00000140  </font>100e3692a28e3220211973d0b14a2dc2 ..6...2 !.s..J-.   100e3692a28e3220211973d0b14a2dc2 ..6...2 !.s..J-.
...
<font color="#CC0000">0x00000160! </font><font color="#4E9A06">599892ccef2cf3ac7f0c075cc4</font><font color="#CC0000">42</font><font color="#4E9A06">58e3</font> <font color="#4E9A06">Y....,.....\.</font><font color="#CC0000">B</font><font color="#4E9A06">X.</font>   <font color="#4E9A06">599892ccef2cf3ac7f0c075cc4</font><font color="#CC0000">43</font><font color="#4E9A06">58e3</font> <font color="#4E9A06">Y....,.....\.</font><font color="#CC0000">C</font><font color="#4E9A06">X.</font>
<font color="#4E9A06">0x00000170  </font>b07de045115bb2c3e50da944ea605f05 .}.E.[.....D.`_.   b07de045115bb2c3e50da944ea605f05 .}.E.[.....D.`_.
<font color="#4E9A06">0x00000180  </font>0d68ea2072be23173b91a78dfa9e183b .h. r.#.;......;   0d68ea2072be23173b91a78dfa9e183b .h. r.#.;......;
...
<font color="#CC0000">0x000001a0! </font><font color="#4E9A06">c7b3f3368c6e860e355abd6ec63aed</font><font color="#CC0000">ac</font> <font color="#4E9A06">...6.n..5Z.n.:.</font><font color="#CC0000">.</font>   <font color="#4E9A06">c7b3f3368c6e860e355abd6ec63aed</font><font color="#CC0000">b4</font> <font color="#4E9A06">...6.n..5Z.n.:.</font><font color="#CC0000">.</font>
<font color="#4E9A06">0x000001b0  </font>a96348cac54a8055ac4a437ff9f8accc .cH..J.U.JC.....   a96348cac54a8055ac4a437ff9f8accc .cH..J.U.JC.....
<font color="#4E9A06">0x000001c0  </font>6ca0c47bcd60828413f22030215fc2e2 l..{.`.... 0!_..   6ca0c47bcd60828413f22030215fc2e2 l..{.`.... 0!_..
...
<font color="#CC0000">0x000001e0! </font><font color="#4E9A06">e4d0d5d533c4d3f4e60b1fca</font><font color="#CC0000">5c</font><font color="#4E9A06">9d67d5</font> <font color="#4E9A06">....3.......</font><font color="#CC0000">\</font><font color="#4E9A06">.g.</font>   <font color="#4E9A06">e4d0d5d533c4d3f4e60b1fca</font><font color="#CC0000">9c</font><font color="#4E9A06">9d67d5</font> <font color="#4E9A06">....3.......</font><font color="#CC0000">.</font><font color="#4E9A06">.g.</font>
<font color="#4E9A06">0x000001f0  </font>60044dac8cb6a5cd5d0fd433c7de1a7f `.M.....]..3....   60044dac8cb6a5cd5d0fd433c7de1a7f `.M.....]..3....
<font color="#4E9A06">0x00000200  </font>3deb06da6f705f1859961e5924ebf8e9 =...op_.Y..Y$...   3deb06da6f705f1859961e5924ebf8e9 =...op_.Y..Y$...
...
<font color="#CC0000">0x00000220! </font><font color="#4E9A06">6ae76fae5f339922cdc1e6366d8e5e</font><font color="#CC0000">33</font> <font color="#4E9A06">j.o._3.&quot;...6m.^</font><font color="#CC0000">3</font>   <font color="#4E9A06">6ae76fae5f339922cdc1e6366d8e5e</font><font color="#CC0000">73</font> <font color="#4E9A06">j.o._3.&quot;...6m.^</font><font color="#CC0000">s</font>
<font color="#4E9A06">0x00000230  </font>ed4ee7a98794b1a05de0df7385d88e84 .N......]..s....   ed4ee7a98794b1a05de0df7385d88e84 .N......]..s....
<font color="#4E9A06">0x00000240  </font>125f239129f65b9c17f390bbe4bbda52 ._#.).[........R   125f239129f65b9c17f390bbe4bbda52 ._#.).[........R
...
<font color="#CC0000">0x00000260! </font><font color="#4E9A06">769bb6ccaf9a56faf48f02fe8d</font><font color="#CC0000">177e</font><font color="#4E9A06">02</font> <font color="#4E9A06">v.....V......</font><font color="#CC0000">.~</font><font color="#4E9A06">.</font>   <font color="#4E9A06">769bb6ccaf9a56faf48f02fe8d</font><font color="#CC0000">f77d</font><font color="#4E9A06">02</font> <font color="#4E9A06">v.....V......</font><font color="#CC0000">.}</font><font color="#4E9A06">.</font>
<font color="#4E9A06">0x00000270  </font>4216e0ff6b4c4fb15441d0cd48641da2 B...kLO.TA..Hd..   4216e0ff6b4c4fb15441d0cd48641da2 B...kLO.TA..Hd..
<font color="#4E9A06">0x00000280  </font>a7c119556394d7969ffc468a50ec2857 ...Uc.....F.P.(W   a7c119556394d7969ffc468a50ec2857 ...Uc.....F.P.(W
...
<font color="#CC0000">0x000002a0! </font><font color="#4E9A06">9fe186d506c1decd0f4a9173</font><font color="#CC0000">4d</font><font color="#4E9A06">ccbd2f</font> <font color="#4E9A06">.........J.s</font><font color="#CC0000">M</font><font color="#4E9A06">../</font>   <font color="#4E9A06">9fe186d506c1decd0f4a9173</font><font color="#CC0000">51</font><font color="#4E9A06">ccbd2f</font> <font color="#4E9A06">.........J.s</font><font color="#CC0000">Q</font><font color="#4E9A06">../</font>
<font color="#4E9A06">0x000002b0  </font>f2c8c5e07d7c29d891364137d08d04e5 ....}|)..6A7....   f2c8c5e07d7c29d891364137d08d04e5 ....}|)..6A7....
</pre>