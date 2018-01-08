Blockly 案例  

姓名：李嘉文

校园卡号：320170928361

所在学院：数学与统计学院

所在年级班级：2017级1班

---

$$x = y$$

#### 案例说明：

###### _如果四边形四个边的长度分别为a,b,c,d，一对对角之和为2\*alpha，则其面积为：_

###### 

**S = √\[\(s-a\)\*\(s-b\)\*\(s-c\)\*\(s-d\)-a\*b\*c\*d\*cos^2\(alpha\)\]**

##### 其中**    **s = 0.5\*\(a+b+c+d\)**  **。

###### _定义一个函数计算任意四边形的面积。设有一个四边形，其四条边边长分别为3，4，5，5，一对对角之和为145°，写程序计算它的面积。_





#### 界面截图：

#### ![](file:///C:\Users\lijia\AppData\Roaming\Tencent\Users\614043087\QQ\WinTemp\RichOle\ERK2BFD}A$%29YJH%0_6TB26G.png)![](/assets/ERK2BFD}A$%29YJH%0_6TB26G.png)



#### 运行结果**截图：**

![](/assets/SV874SVF2KDP%28%29$5PD%28W_[T.png)

![](/assets/O5GPP8%29`%28%28UVFK9X@I99FE0.png)

![](/assets/W3A]KV$6YH%28`%29}YJ5`U%29HUY.png)

![](/assets/5YTEZTB{Z_PZK3DUTSJS5~J.png)

![](/assets/import.png)

![](/assets/F{N$OR1W7%29%28PJN[T9JXQ{8O.png)

![](/assets/8L%293FAQ7%28AL{75%1AD1YTSP.png)

#### XML代码**：**



&lt;xml xmlns="http://www.w3.org/1999/xhtml"&gt;

  &lt;variables&gt;

    &lt;variable type="" id="-7r,9nZ1PGu\(^}bn1^Pc"&gt;a&lt;/variable&gt;

    &lt;variable type="" id="DJETl!Q\*\|2L}JMeD0mok"&gt;b&lt;/variable&gt;

    &lt;variable type="" id="YXToNQeI}9B.$%lRTcw3"&gt;c&lt;/variable&gt;

    &lt;variable type="" id="@YJ\(HmYyDw%}wDiMS\#}m"&gt;d&lt;/variable&gt;

    &lt;variable type="" id="%Edq-\`\|.LR\_p%dKhy\*qI"&gt;alpha&lt;/variable&gt;

    &lt;variable type="" id="~:iv{JnK7Ri2?^t,\|K6v"&gt;x&lt;/variable&gt;

    &lt;variable type="" id="^M\*~:~Sxj2@fmEC02\(3\)"&gt;temp1&lt;/variable&gt;

    &lt;variable type="" id="YpZD\)HZ?GJ\#NL4phWX5\*"&gt;temp2&lt;/variable&gt;

    &lt;variable type="" id=";K,\_UBiYHsW7C-7gb7}g"&gt;S&lt;/variable&gt;

  &lt;/variables&gt;

  &lt;block type="text\_print" id="\]z0iIrYo{DU4=6Y\`MI{0" x="162" y="-12"&gt;

    &lt;value name="TEXT"&gt;

      &lt;shadow type="text" id="?n\(@f$UG/\):\*W\|Sifosd"&gt;

        &lt;field name="TEXT"&gt;abc&lt;/field&gt;

      &lt;/shadow&gt;

      &lt;block type="text" id="5XKI2r\]EBKtq\#O@V\)!Jk"&gt;

        &lt;field name="TEXT"&gt;请依次输入四边形的四个边a,b,c,d和一对角之和的一半alpha&lt;/field&gt;

      &lt;/block&gt;

    &lt;/value&gt;

    &lt;next&gt;

      &lt;block type="variables\_set" id="KtxtE/?GXznKTbTOjq+R"&gt;

        &lt;field name="VAR" id="-7r,9nZ1PGu\(^}bn1^Pc" variabletype=""&gt;a&lt;/field&gt;

        &lt;value name="VALUE"&gt;

          &lt;block type="text\_prompt\_ext" id="g\(7}9^y0lTcW/n5D;d0H"&gt;

            &lt;mutation type="NUMBER"&gt;&lt;/mutation&gt;

            &lt;field name="TYPE"&gt;NUMBER&lt;/field&gt;

            &lt;value name="TEXT"&gt;

              &lt;shadow type="text" id="C\]\*.H\|\`/\_tu6\[yu\*9tAV"&gt;

                &lt;field name="TEXT"&gt;abc&lt;/field&gt;

              &lt;/shadow&gt;

              &lt;block type="text" id="N{Cr=@@8TFp\)}OQz!o=R"&gt;

                &lt;field name="TEXT"&gt;&lt;/field&gt;

              &lt;/block&gt;

            &lt;/value&gt;

          &lt;/block&gt;

        &lt;/value&gt;

        &lt;next&gt;

          &lt;block type="variables\_set" id="-VgnBN5E$lo\`XDF{jWD\|"&gt;

            &lt;field name="VAR" id="DJETl!Q\*\|2L}JMeD0mok" variabletype=""&gt;b&lt;/field&gt;

            &lt;value name="VALUE"&gt;

              &lt;block type="text\_prompt\_ext" id="J;+sjBtN@6yD.^PVud\)u"&gt;

                &lt;mutation type="NUMBER"&gt;&lt;/mutation&gt;

                &lt;field name="TYPE"&gt;NUMBER&lt;/field&gt;

                &lt;value name="TEXT"&gt;

                  &lt;shadow type="text" id="nGHTF\`\)gD9~lP\]-of0k\|"&gt;

                    &lt;field name="TEXT"&gt;abc&lt;/field&gt;

                  &lt;/shadow&gt;

                  &lt;block type="text" id="xWx0pfc\]B{8;2C6A%xf4"&gt;

                    &lt;field name="TEXT"&gt;&lt;/field&gt;

                  &lt;/block&gt;

                &lt;/value&gt;

              &lt;/block&gt;

            &lt;/value&gt;

            &lt;next&gt;

              &lt;block type="variables\_set" id="abA,BRELYCJLDDU{7!n\)"&gt;

                &lt;field name="VAR" id="YXToNQeI}9B.$%lRTcw3" variabletype=""&gt;c&lt;/field&gt;

                &lt;value name="VALUE"&gt;

                  &lt;block type="text\_prompt\_ext" id="=bp9mYMVNCBW9,Mpe\(VW"&gt;

                    &lt;mutation type="NUMBER"&gt;&lt;/mutation&gt;

                    &lt;field name="TYPE"&gt;NUMBER&lt;/field&gt;

                    &lt;value name="TEXT"&gt;

                      &lt;shadow type="text" id=":\[+DFI@ERxvs\`8{-V1~l"&gt;

                        &lt;field name="TEXT"&gt;abc&lt;/field&gt;

                      &lt;/shadow&gt;

                      &lt;block type="text" id="Brg8\#Zfw8TlVjtpfQ4g\#"&gt;

                        &lt;field name="TEXT"&gt;&lt;/field&gt;

                      &lt;/block&gt;

                    &lt;/value&gt;

                  &lt;/block&gt;

                &lt;/value&gt;

                &lt;next&gt;

                  &lt;block type="variables\_set" id="F\[jOZgP\#K6Jn3XvMkc1G"&gt;

                    &lt;field name="VAR" id="@YJ\(HmYyDw%}wDiMS\#}m" variabletype=""&gt;d&lt;/field&gt;

                    &lt;value name="VALUE"&gt;

                      &lt;block type="text\_prompt\_ext" id="h8SA@si}J}W:NuiwY5b}"&gt;

                        &lt;mutation type="NUMBER"&gt;&lt;/mutation&gt;

                        &lt;field name="TYPE"&gt;NUMBER&lt;/field&gt;

                        &lt;value name="TEXT"&gt;

                          &lt;shadow type="text" id="r39Nlhs^\(xU0@Oy.J5RQ"&gt;

                            &lt;field name="TEXT"&gt;abc&lt;/field&gt;

                          &lt;/shadow&gt;

                          &lt;block type="text" id="@\`^1HZ-z~9ehsaq.dDj;"&gt;

                            &lt;field name="TEXT"&gt;&lt;/field&gt;

                          &lt;/block&gt;

                        &lt;/value&gt;

                      &lt;/block&gt;

                    &lt;/value&gt;

                    &lt;next&gt;

                      &lt;block type="variables\_set" id="We1,\]}=~{\_2nDZ:.v\*Km"&gt;

                        &lt;field name="VAR" id="%Edq-\`\|.LR\_p%dKhy\*qI" variabletype=""&gt;alpha&lt;/field&gt;

                        &lt;value name="VALUE"&gt;

                          &lt;block type="text\_prompt\_ext" id="Mckl\`J;nhJEo\[Qk/C~mZ"&gt;

                            &lt;mutation type="NUMBER"&gt;&lt;/mutation&gt;

                            &lt;field name="TYPE"&gt;NUMBER&lt;/field&gt;

                            &lt;value name="TEXT"&gt;

                              &lt;shadow type="text" id="r39Nlhs^\(xU0@Oy.J5RQ"&gt;

                                &lt;field name="TEXT"&gt;abc&lt;/field&gt;

                              &lt;/shadow&gt;

                              &lt;block type="text" id="Y6ZR09\`jNs3aTdgMP=Uj"&gt;

                                &lt;field name="TEXT"&gt;&lt;/field&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                          &lt;/block&gt;

                        &lt;/value&gt;

                        &lt;next&gt;

                          &lt;block type="variables\_set" id=",sn34rN3G;:up}vKS;8c"&gt;

                            &lt;field name="VAR" id="~:iv{JnK7Ri2?^t,\|K6v" variabletype=""&gt;x&lt;/field&gt;

                            &lt;value name="VALUE"&gt;

                              &lt;block type="math\_arithmetic" id="f,=!mP5^%3k5,62XjF9^"&gt;

                                &lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

                                &lt;value name="A"&gt;

                                  &lt;shadow type="math\_number" id="pCR@zlze5XN%\*+1\[^IH7"&gt;

                                    &lt;field name="NUM"&gt;0.5&lt;/field&gt;

                                  &lt;/shadow&gt;

                                  &lt;block type="math\_number" id="=N;mLH4,LXeAyH4dV}Wt"&gt;

                                    &lt;field name="NUM"&gt;0.5&lt;/field&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                                &lt;value name="B"&gt;

                                  &lt;shadow type="math\_number" id="j\`qKBn^Y7Ezis2?=d.8v"&gt;

                                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                                  &lt;/shadow&gt;

                                  &lt;block type="math\_arithmetic" id="chW\*C,~ISg2{z;6:CO1g"&gt;

                                    &lt;field name="OP"&gt;ADD&lt;/field&gt;

                                    &lt;value name="A"&gt;

                                      &lt;shadow type="math\_number" id="lC?Y=Ejl6V7rNCM3\)Ne!"&gt;

                                        &lt;field name="NUM"&gt;1&lt;/field&gt;

                                      &lt;/shadow&gt;

                                      &lt;block type="variables\_get" id="mW\[u~\#LiVN1~:FI\#/Ek3"&gt;

                                        &lt;field name="VAR" id="-7r,9nZ1PGu\(^}bn1^Pc" variabletype=""&gt;a&lt;/field&gt;

                                      &lt;/block&gt;

                                    &lt;/value&gt;

                                    &lt;value name="B"&gt;

                                      &lt;shadow type="math\_number" id="H/cYn.h~5MTWd=8Qn}iH"&gt;

                                        &lt;field name="NUM"&gt;1&lt;/field&gt;

                                      &lt;/shadow&gt;

                                      &lt;block type="math\_arithmetic" id="SRi\_UC=?BmtR\#@:D{?ir"&gt;

                                        &lt;field name="OP"&gt;ADD&lt;/field&gt;

                                        &lt;value name="A"&gt;

                                          &lt;shadow type="math\_number" id="YNDTp;AQ\`:H%f,Jp\*\*dM"&gt;

                                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                                          &lt;/shadow&gt;

                                          &lt;block type="variables\_get" id="lz\|TI8?\`!R^@\_Mkse@:1"&gt;

                                            &lt;field name="VAR" id="DJETl!Q\*\|2L}JMeD0mok" variabletype=""&gt;b&lt;/field&gt;

                                          &lt;/block&gt;

                                        &lt;/value&gt;

                                        &lt;value name="B"&gt;

                                          &lt;shadow type="math\_number" id="aS/wdw}BkSqEG\|@UJ{@H"&gt;

                                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                                          &lt;/shadow&gt;

                                          &lt;block type="math\_arithmetic" id="6m\(QrIM5ES,?ZRa\#~2k3"&gt;

                                            &lt;field name="OP"&gt;ADD&lt;/field&gt;

                                            &lt;value name="A"&gt;

                                              &lt;shadow type="math\_number" id="Sj;2W^OA0%mt!3hjgPF+"&gt;

                                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                                              &lt;/shadow&gt;

                                              &lt;block type="variables\_get" id=":P%^\]bfi4DKiI+t{?Zap"&gt;

                                                &lt;field name="VAR" id="YXToNQeI}9B.$%lRTcw3" variabletype=""&gt;c&lt;/field&gt;

                                              &lt;/block&gt;

                                            &lt;/value&gt;

                                            &lt;value name="B"&gt;

                                              &lt;shadow type="math\_number" id=".\_WS/L9kgdBesGPC3D^?"&gt;

                                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                                              &lt;/shadow&gt;

                                              &lt;block type="variables\_get" id="2MZVQ,NS9YM8VjRy\)VLR"&gt;

                                                &lt;field name="VAR" id="@YJ\(HmYyDw%}wDiMS\#}m" variabletype=""&gt;d&lt;/field&gt;

                                              &lt;/block&gt;

                                            &lt;/value&gt;

                                          &lt;/block&gt;

                                        &lt;/value&gt;

                                      &lt;/block&gt;

                                    &lt;/value&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                              &lt;/block&gt;

                            &lt;/value&gt;

                            &lt;next&gt;

                              &lt;block type="variables\_set" id="3ySkW\#9A\]GnWM/p:ZYl{"&gt;

                                &lt;field name="VAR" id="^M\*~:~Sxj2@fmEC02\(3\)" variabletype=""&gt;temp1&lt;/field&gt;

                                &lt;value name="VALUE"&gt;

                                  &lt;block type="math\_arithmetic" id="B}qez14h\_N\].DnJ9uYJ/"&gt;

                                    &lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

                                    &lt;value name="A"&gt;

                                      &lt;shadow type="math\_number" id="Iu\#-Rk8%Ah~3P;lWjcPQ"&gt;

                                        &lt;field name="NUM"&gt;1&lt;/field&gt;

                                      &lt;/shadow&gt;

                                      &lt;block type="math\_arithmetic" id="\#7}\]kA+vCdQ5nDl~\#Isa"&gt;

                                        &lt;field name="OP"&gt;MINUS&lt;/field&gt;

                                        &lt;value name="A"&gt;

                                          &lt;shadow type="math\_number" id="\(E/f7:,Uu1jv.Zp6?h+a"&gt;

                                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                                          &lt;/shadow&gt;

                                          &lt;block type="variables\_get" id="\[bmtnnJ\_ia@u\]N8Qc.^R"&gt;

                                            &lt;field name="VAR" id="~:iv{JnK7Ri2?^t,\|K6v" variabletype=""&gt;x&lt;/field&gt;

                                          &lt;/block&gt;

                                        &lt;/value&gt;

                                        &lt;value name="B"&gt;

                                          &lt;shadow type="math\_number" id="0\]$B8@JLeK7K:5uLI!\)w"&gt;

                                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                                          &lt;/shadow&gt;

                                          &lt;block type="variables\_get" id="J!B9?E-TS6\]RW6Y\]K34W"&gt;

                                            &lt;field name="VAR" id="-7r,9nZ1PGu\(^}bn1^Pc" variabletype=""&gt;a&lt;/field&gt;

                                          &lt;/block&gt;

                                        &lt;/value&gt;

                                      &lt;/block&gt;

                                    &lt;/value&gt;

                                    &lt;value name="B"&gt;

                                      &lt;shadow type="math\_number" id="^brw\]YPJqp9AqaW,y9F="&gt;

                                        &lt;field name="NUM"&gt;1&lt;/field&gt;

                                      &lt;/shadow&gt;

                                      &lt;block type="math\_arithmetic" id="SAJ\|HU1VJ^iDf\_EJ.net"&gt;

                                        &lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

                                        &lt;value name="A"&gt;

                                          &lt;shadow type="math\_number" id="1K4TVT9%\*1@ZdbpXPu\(!"&gt;

                                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                                          &lt;/shadow&gt;

                                          &lt;block type="math\_arithmetic" id=":AYb?.T29\_=\_RdwfJXL5"&gt;

                                            &lt;field name="OP"&gt;MINUS&lt;/field&gt;

                                            &lt;value name="A"&gt;

                                              &lt;shadow type="math\_number" id="\(E/f7:,Uu1jv.Zp6?h+a"&gt;

                                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                                              &lt;/shadow&gt;

                                              &lt;block type="variables\_get" id="?Hx8=\#/lvK-Oc\[Kl\(k3M"&gt;

                                                &lt;field name="VAR" id="~:iv{JnK7Ri2?^t,\|K6v" variabletype=""&gt;x&lt;/field&gt;

                                              &lt;/block&gt;

                                            &lt;/value&gt;

                                            &lt;value name="B"&gt;

                                              &lt;shadow type="math\_number" id="0\]$B8@JLeK7K:5uLI!\)w"&gt;

                                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                                              &lt;/shadow&gt;

                                              &lt;block type="variables\_get" id="D?1gyNaS\`\_}{+f^x2FU2"&gt;

                                                &lt;field name="VAR" id="DJETl!Q\*\|2L}JMeD0mok" variabletype=""&gt;b&lt;/field&gt;

                                              &lt;/block&gt;

                                            &lt;/value&gt;

                                          &lt;/block&gt;

                                        &lt;/value&gt;

                                        &lt;value name="B"&gt;

                                          &lt;shadow type="math\_number" id="u$;J,85AGw\*grU\(^J/ga"&gt;

                                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                                          &lt;/shadow&gt;

                                          &lt;block type="math\_arithmetic" id="mE:;9!qR}BTVw/-.j52Q"&gt;

                                            &lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

                                            &lt;value name="A"&gt;

                                              &lt;shadow type="math\_number" id="3\|Ug;,E^69hYe%;zRJnZ"&gt;

                                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                                              &lt;/shadow&gt;

                                              &lt;block type="math\_arithmetic" id="\[u~\]4R8S,CtXw}}^XC.\|"&gt;

                                                &lt;field name="OP"&gt;MINUS&lt;/field&gt;

                                                &lt;value name="A"&gt;

                                                  &lt;shadow type="math\_number" id="\(E/f7:,Uu1jv.Zp6?h+a"&gt;

                                                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                  &lt;/shadow&gt;

                                                  &lt;block type="variables\_get" id="t76pt\[!^6hDdQ5K\|f?zR"&gt;

                                                    &lt;field name="VAR" id="~:iv{JnK7Ri2?^t,\|K6v" variabletype=""&gt;x&lt;/field&gt;

                                                  &lt;/block&gt;

                                                &lt;/value&gt;

                                                &lt;value name="B"&gt;

                                                  &lt;shadow type="math\_number" id="0\]$B8@JLeK7K:5uLI!\)w"&gt;

                                                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                  &lt;/shadow&gt;

                                                  &lt;block type="variables\_get" id="\*v\)7CR0\#M/.\#87~\[9m6:"&gt;

                                                    &lt;field name="VAR" id="YXToNQeI}9B.$%lRTcw3" variabletype=""&gt;c&lt;/field&gt;

                                                  &lt;/block&gt;

                                                &lt;/value&gt;

                                              &lt;/block&gt;

                                            &lt;/value&gt;

                                            &lt;value name="B"&gt;

                                              &lt;shadow type="math\_number" id="D9Z;Z\#D!4AZ{z\)s\|\[+2l"&gt;

                                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                                              &lt;/shadow&gt;

                                              &lt;block type="math\_arithmetic" id="Ber3{D\`.$S2Y1e1\`wETb"&gt;

                                                &lt;field name="OP"&gt;MINUS&lt;/field&gt;

                                                &lt;value name="A"&gt;

                                                  &lt;shadow type="math\_number" id="\(E/f7:,Uu1jv.Zp6?h+a"&gt;

                                                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                  &lt;/shadow&gt;

                                                  &lt;block type="variables\_get" id="%c2@FwPj:zH1w\[.:g^jw"&gt;

                                                    &lt;field name="VAR" id="~:iv{JnK7Ri2?^t,\|K6v" variabletype=""&gt;x&lt;/field&gt;

                                                  &lt;/block&gt;

                                                &lt;/value&gt;

                                                &lt;value name="B"&gt;

                                                  &lt;shadow type="math\_number" id="0\]$B8@JLeK7K:5uLI!\)w"&gt;

                                                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                  &lt;/shadow&gt;

                                                  &lt;block type="variables\_get" id="Gm}%8LDz0.ppl\(4\_^dS7"&gt;

                                                    &lt;field name="VAR" id="@YJ\(HmYyDw%}wDiMS\#}m" variabletype=""&gt;d&lt;/field&gt;

                                                  &lt;/block&gt;

                                                &lt;/value&gt;

                                              &lt;/block&gt;

                                            &lt;/value&gt;

                                          &lt;/block&gt;

                                        &lt;/value&gt;

                                      &lt;/block&gt;

                                    &lt;/value&gt;

                                  &lt;/block&gt;

                                &lt;/value&gt;

                                &lt;next&gt;

                                  &lt;block type="variables\_set" id="K\[\_$geSYT%W,3\#K\_:bqT"&gt;

                                    &lt;field name="VAR" id="YpZD\)HZ?GJ\#NL4phWX5\*" variabletype=""&gt;temp2&lt;/field&gt;

                                    &lt;value name="VALUE"&gt;

                                      &lt;block type="math\_arithmetic" id="Mf!A~VGx-C?I0\[YkL?6R"&gt;

                                        &lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

                                        &lt;value name="A"&gt;

                                          &lt;shadow type="math\_number" id="\(E/f7:,Uu1jv.Zp6?h+a"&gt;

                                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                                          &lt;/shadow&gt;

                                          &lt;block type="variables\_get" id="DFb24N4zH?W\_R@yjr2{0"&gt;

                                            &lt;field name="VAR" id="-7r,9nZ1PGu\(^}bn1^Pc" variabletype=""&gt;a&lt;/field&gt;

                                          &lt;/block&gt;

                                        &lt;/value&gt;

                                        &lt;value name="B"&gt;

                                          &lt;shadow type="math\_number" id="0\]$B8@JLeK7K:5uLI!\)w"&gt;

                                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                                          &lt;/shadow&gt;

                                          &lt;block type="math\_arithmetic" id="=ts\_X/yyQ!W\#hE=K=Dq?"&gt;

                                            &lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

                                            &lt;value name="A"&gt;

                                              &lt;shadow type="math\_number" id="\(E/f7:,Uu1jv.Zp6?h+a"&gt;

                                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                                              &lt;/shadow&gt;

                                              &lt;block type="variables\_get" id="akMf/6VNS+RksFJ%67dh"&gt;

                                                &lt;field name="VAR" id="DJETl!Q\*\|2L}JMeD0mok" variabletype=""&gt;b&lt;/field&gt;

                                              &lt;/block&gt;

                                            &lt;/value&gt;

                                            &lt;value name="B"&gt;

                                              &lt;shadow type="math\_number" id="0\]$B8@JLeK7K:5uLI!\)w"&gt;

                                                &lt;field name="NUM"&gt;1&lt;/field&gt;

                                              &lt;/shadow&gt;

                                              &lt;block type="math\_arithmetic" id="%jx\_3~R5q\|\]!wmGbOJlm"&gt;

                                                &lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

                                                &lt;value name="A"&gt;

                                                  &lt;shadow type="math\_number" id="\(E/f7:,Uu1jv.Zp6?h+a"&gt;

                                                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                  &lt;/shadow&gt;

                                                  &lt;block type="variables\_get" id="2;vzu\]\(RND!OY9hx\|Iwh"&gt;

                                                    &lt;field name="VAR" id="YXToNQeI}9B.$%lRTcw3" variabletype=""&gt;c&lt;/field&gt;

                                                  &lt;/block&gt;

                                                &lt;/value&gt;

                                                &lt;value name="B"&gt;

                                                  &lt;shadow type="math\_number" id="0\]$B8@JLeK7K:5uLI!\)w"&gt;

                                                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                  &lt;/shadow&gt;

                                                  &lt;block type="math\_arithmetic" id="-~G2KK\]cFI~0~Xj4mZV6"&gt;

                                                    &lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

                                                    &lt;value name="A"&gt;

                                                      &lt;shadow type="math\_number" id="\(E/f7:,Uu1jv.Zp6?h+a"&gt;

                                                        &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                      &lt;/shadow&gt;

                                                      &lt;block type="variables\_get" id="0oAV0Ih\(\)wxU}6Xn9A2q"&gt;

                                                        &lt;field name="VAR" id="@YJ\(HmYyDw%}wDiMS\#}m" variabletype=""&gt;d&lt;/field&gt;

                                                      &lt;/block&gt;

                                                    &lt;/value&gt;

                                                    &lt;value name="B"&gt;

                                                      &lt;shadow type="math\_number" id="0\]$B8@JLeK7K:5uLI!\)w"&gt;

                                                        &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                      &lt;/shadow&gt;

                                                      &lt;block type="math\_arithmetic" id="qyzekF~\#BixNj8V58\[4F"&gt;

                                                        &lt;field name="OP"&gt;MULTIPLY&lt;/field&gt;

                                                        &lt;value name="A"&gt;

                                                          &lt;shadow type="math\_number" id="I0bCjk\`!^R/vkLB,\]ZTB"&gt;

                                                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                          &lt;/shadow&gt;

                                                          &lt;block type="math\_trig" id="9TJp?\#pAk!VKtGSRaW8{"&gt;

                                                            &lt;field name="OP"&gt;COS&lt;/field&gt;

                                                            &lt;value name="NUM"&gt;

                                                              &lt;shadow type="math\_number" id="\`7p4N\#Csu,CSd\(S@eAAw"&gt;

                                                                &lt;field name="NUM"&gt;45&lt;/field&gt;

                                                              &lt;/shadow&gt;

                                                              &lt;block type="variables\_get" id="\_gT\)Qz\_4Z^4Njwf+hL9g"&gt;

                                                                &lt;field name="VAR" id="%Edq-\`\|.LR\_p%dKhy\*qI" variabletype=""&gt;alpha&lt;/field&gt;

                                                              &lt;/block&gt;

                                                            &lt;/value&gt;

                                                          &lt;/block&gt;

                                                        &lt;/value&gt;

                                                        &lt;value name="B"&gt;

                                                          &lt;shadow type="math\_number" id="3hzY\)uM\`VBX\)3BcB1=x~"&gt;

                                                            &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                          &lt;/shadow&gt;

                                                          &lt;block type="math\_trig" id="Dq,s%E0dC\`X\($D4gY\`2-"&gt;

                                                            &lt;field name="OP"&gt;COS&lt;/field&gt;

                                                            &lt;value name="NUM"&gt;

                                                              &lt;shadow type="math\_number" id="\`7p4N\#Csu,CSd\(S@eAAw"&gt;

                                                                &lt;field name="NUM"&gt;45&lt;/field&gt;

                                                              &lt;/shadow&gt;

                                                              &lt;block type="variables\_get" id="OV!2jK!T\*!wawr\)E9tPn"&gt;

                                                                &lt;field name="VAR" id="%Edq-\`\|.LR\_p%dKhy\*qI" variabletype=""&gt;alpha&lt;/field&gt;

                                                              &lt;/block&gt;

                                                            &lt;/value&gt;

                                                          &lt;/block&gt;

                                                        &lt;/value&gt;

                                                      &lt;/block&gt;

                                                    &lt;/value&gt;

                                                  &lt;/block&gt;

                                                &lt;/value&gt;

                                              &lt;/block&gt;

                                            &lt;/value&gt;

                                          &lt;/block&gt;

                                        &lt;/value&gt;

                                      &lt;/block&gt;

                                    &lt;/value&gt;

                                    &lt;next&gt;

                                      &lt;block type="variables\_set" id="b9l}fh7JQK6o3CpKyzO@"&gt;

                                        &lt;field name="VAR" id=";K,\_UBiYHsW7C-7gb7}g" variabletype=""&gt;S&lt;/field&gt;

                                        &lt;value name="VALUE"&gt;

                                          &lt;block type="math\_single" id="g\`?La,?{/59\_9mAUaQ03"&gt;

                                            &lt;field name="OP"&gt;ROOT&lt;/field&gt;

                                            &lt;value name="NUM"&gt;

                                              &lt;shadow type="math\_number" id="CXC,5Cn,2eguv\]M\`~hd\)"&gt;

                                                &lt;field name="NUM"&gt;9&lt;/field&gt;

                                              &lt;/shadow&gt;

                                              &lt;block type="math\_arithmetic" id="eT\`y!Br50P?MYHobm$zL"&gt;

                                                &lt;field name="OP"&gt;MINUS&lt;/field&gt;

                                                &lt;value name="A"&gt;

                                                  &lt;shadow type="math\_number" id="Ie~J{9E~M/a.\)0Hk+\`3F"&gt;

                                                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                  &lt;/shadow&gt;

                                                  &lt;block type="variables\_get" id="pXD2N}mB{7{3nsp;DG\*p"&gt;

                                                    &lt;field name="VAR" id="^M\*~:~Sxj2@fmEC02\(3\)" variabletype=""&gt;temp1&lt;/field&gt;

                                                  &lt;/block&gt;

                                                &lt;/value&gt;

                                                &lt;value name="B"&gt;

                                                  &lt;shadow type="math\_number" id="+/gtnZxu\|rc4rg:;Zx5V"&gt;

                                                    &lt;field name="NUM"&gt;1&lt;/field&gt;

                                                  &lt;/shadow&gt;

                                                  &lt;block type="variables\_get" id="Qb\|AK=AhGi44yatnkIEb"&gt;

                                                    &lt;field name="VAR" id="YpZD\)HZ?GJ\#NL4phWX5\*" variabletype=""&gt;temp2&lt;/field&gt;

                                                  &lt;/block&gt;

                                                &lt;/value&gt;

                                              &lt;/block&gt;

                                            &lt;/value&gt;

                                          &lt;/block&gt;

                                        &lt;/value&gt;

                                        &lt;next&gt;

                                          &lt;block type="text\_print" id="fhO8H/7mS;M2e}6tM/Q\#"&gt;

                                            &lt;value name="TEXT"&gt;

                                              &lt;shadow type="text" id="P8R\)l^\|G}\_ZE-,%Ug\_6Y"&gt;

                                                &lt;field name="TEXT"&gt;abc&lt;/field&gt;

                                              &lt;/shadow&gt;

                                              &lt;block type="variables\_get" id="1DEpClD!mkj,tB\[zKC-b"&gt;

                                                &lt;field name="VAR" id=";K,\_UBiYHsW7C-7gb7}g" variabletype=""&gt;S&lt;/field&gt;

                                              &lt;/block&gt;

                                            &lt;/value&gt;

                                          &lt;/block&gt;

                                        &lt;/next&gt;

                                      &lt;/block&gt;

                                    &lt;/next&gt;

                                  &lt;/block&gt;

                                &lt;/next&gt;

                              &lt;/block&gt;

                            &lt;/next&gt;

                          &lt;/block&gt;

                        &lt;/next&gt;

                      &lt;/block&gt;

                    &lt;/next&gt;

                  &lt;/block&gt;

                &lt;/next&gt;

              &lt;/block&gt;

            &lt;/next&gt;

          &lt;/block&gt;

        &lt;/next&gt;

      &lt;/block&gt;

    &lt;/next&gt;

  &lt;/block&gt;

&lt;/xml&gt;































