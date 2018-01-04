
BLOCKLY案例 
         二组 邹嘉龙 数学院 学号 320170923381
案例说明
一个三位的十进制整数，如果其三个数字之立方和等于它的数值，他被称为“水仙花数”，反之，则不是“水仙花数”。定义函数判断一个整数是否为水仙花数。

模块截图

![](/assets/板块.png)


结果显示

![](/assets/结果显示.jpg)


XML代码

<xml xmlns="http://www.w3.org/1999/xhtml">
  <variables>
    <variable type="" id="vwt!XWb/7O*tUiJxp+*b">x</variable>
    <variable type="" id="R%;fDF9FEPFO~TudO}Lx">k</variable>
    <variable type="" id="t^LNI[nk(Zv@KGPO5OY|">m</variable>
    <variable type="" id="CY][g[.?t1Te3;[YEyrq">s</variable>
    <variable type="" id="Hbsx~`ekgc1O5U_0S|UC">j</variable>
    <variable type="" id=":Q*89vms0)XU]voU=IvC">h</variable>
    <variable type="" id="KrWg%,}}HyVOBG=_~^*/">n</variable>
  </variables>
  <block type="variables_set" id="TPd;if4-708y[mK}_4S(" x="-712" y="363">
    <field name="VAR" id="KrWg%,}}HyVOBG=_~^*/" variabletype="">n</field>
    <value name="VALUE">
      <block type="math_number" id="J}=H@}gKM6OrdK.p1{@9">
        <field name="NUM">123</field>
      </block>
    </value>
    <next>
      <block type="variables_set" id="=4]KqrGCUG5Z!(7I{7?r">
        <field name="VAR" id="R%;fDF9FEPFO~TudO}Lx" variabletype="">k</field>
        <value name="VALUE">
          <block type="math_arithmetic" id="55kU8aS^XGX;S1?bZ+Q+">
            <field name="OP">DIVIDE</field>
            <value name="A">
              <shadow type="math_number" id="@Wj4?A/CqEubF@/j|)qn">
                <field name="NUM">1</field>
              </shadow>
              <block type="variables_get" id="8J?G/NwHgQ%y=/~S.J7F">
                <field name="VAR" id="KrWg%,}}HyVOBG=_~^*/" variabletype="">n</field>
              </block>
            </value>
            <value name="B">
              <shadow type="math_number" id="1JG95D[Jk2H64-$FQ!ba">
                <field name="NUM">100</field>
              </shadow>
            </value>
          </block>
        </value>
        <next>
          <block type="variables_set" id="?#_}!7aKQ=a`+ZA4DkYp">
            <field name="VAR" id=":Q*89vms0)XU]voU=IvC" variabletype="">h</field>
            <value name="VALUE">
              <block type="math_modulo" id="@/JQ.OJdm-BoS$WioRq[">
                <value name="DIVIDEND">
                  <shadow type="math_number" id="+HXwU{)$4%I+V]ix#KwT">
                    <field name="NUM">64</field>
                  </shadow>
                  <block type="math_arithmetic" id="-GMzoqXCdypdt0yw?i.%">
                    <field name="OP">DIVIDE</field>
                    <value name="A">
                      <shadow type="math_number" id="KrjWBMoT5kXmhF@3XR!6">
                        <field name="NUM">1</field>
                      </shadow>
                      <block type="variables_get" id="Cf%{ri:?NHR9VEt+{^ue">
                        <field name="VAR" id="KrWg%,}}HyVOBG=_~^*/" variabletype="">n</field>
                      </block>
                    </value>
                    <value name="B">
                      <shadow type="math_number" id="PwgR*_Q_XJj/rmU^J/4R">
                        <field name="NUM">10</field>
                      </shadow>
                    </value>
                  </block>
                </value>
                <value name="DIVISOR">
                  <shadow type="math_number" id="X!D.}@lkE%Wo/.j)+GRq">
                    <field name="NUM">10</field>
                  </shadow>
                </value>
              </block>
            </value>
            <next>
              <block type="variables_set" id="N`.)9Se1QHU5DcKbyw{=">
                <field name="VAR" id="t^LNI[nk(Zv@KGPO5OY|" variabletype="">m</field>
                <value name="VALUE">
                  <block type="math_arithmetic" id="4[W9~2=Nv?Q!fU-I3oUV">
                    <field name="OP">MINUS</field>
                    <value name="A">
                      <shadow type="math_number" id="2^]R2`]m:+M8_DpJ3#Cp">
                        <field name="NUM">1</field>
                      </shadow>
                      <block type="variables_get" id="-vQ4aBREP2=7iN]%v,-`">
                        <field name="VAR" id="KrWg%,}}HyVOBG=_~^*/" variabletype="">n</field>
                      </block>
                    </value>
                    <value name="B">
                      <shadow type="math_number" id="?I7XT/zk^8,ThH2T^(*%">
                        <field name="NUM">1</field>
                      </shadow>
                      <block type="math_arithmetic" id=",IgBOv)kKP#(f2:{d:z}">
                        <field name="OP">ADD</field>
                        <value name="A">
                          <shadow type="math_number" id="#Tgw#`CKIEV!u^ijzGY}">
                            <field name="NUM">1</field>
                          </shadow>
                          <block type="math_arithmetic" id="GODxEJ@FEMTicxkD^$=(">
                            <field name="OP">MULTIPLY</field>
                            <value name="A">
                              <shadow type="math_number" id="{YAqNIlhYdkRrlm8P$FW">
                                <field name="NUM">1</field>
                              </shadow>
                              <block type="variables_get" id="TOqk)6uVU3[GIaf0lW`Q">
                                <field name="VAR" id="R%;fDF9FEPFO~TudO}Lx" variabletype="">k</field>
                              </block>
                            </value>
                            <value name="B">
                              <shadow type="math_number" id="?GKx(CoL5L|r$3o8l)$%">
                                <field name="NUM">100</field>
                              </shadow>
                            </value>
                          </block>
                        </value>
                        <value name="B">
                          <shadow type="math_number" id="?_m_wN-;9%TWB_ohpC)K">
                            <field name="NUM">1</field>
                          </shadow>
                          <block type="math_arithmetic" id="HeB=i9t)Vxa]`jT+BE2Y">
                            <field name="OP">MULTIPLY</field>
                            <value name="A">
                              <shadow type="math_number" id="G^9*U2JIt}x.59PqcTSM">
                                <field name="NUM">1</field>
                              </shadow>
                              <block type="variables_get" id="DLjEjf0eaR3_5boGE^p(">
                                <field name="VAR" id=":Q*89vms0)XU]voU=IvC" variabletype="">h</field>
                              </block>
                            </value>
                            <value name="B">
                              <shadow type="math_number" id="UG8JKHNATF`mjU*zsOiy">
                                <field name="NUM">10</field>
                              </shadow>
                            </value>
                          </block>
                        </value>
                      </block>
                    </value>
                  </block>
                </value>
                <next>
                  <block type="controls_if" id="_)m672S6Q%[D3k;1-3eA">
                    <mutation else="1"></mutation>
                    <value name="IF0">
                      <block type="logic_compare" id="`!`{{k[~,E#oxK-V2O=T">
                        <field name="OP">NEQ</field>
                        <value name="A">
                          <block type="math_arithmetic" id="@():WL2=]8C#`0PL/~e=">
                            <field name="OP">ADD</field>
                            <value name="A">
                              <shadow type="math_number" id="f`;qO,1|}G{_G(`,;!Mh">
                                <field name="NUM">1</field>
                              </shadow>
                              <block type="math_arithmetic" id="p}]WBYQI.Arn]n+pbCr$">
                                <field name="OP">ADD</field>
                                <value name="A">
                                  <shadow type="math_number" id=":}mBlS8#[mTg5M}{;#GV">
                                    <field name="NUM">1</field>
                                  </shadow>
                                  <block type="math_arithmetic" id="5)W,09fOg11XzPGx??U/">
                                    <field name="OP">MULTIPLY</field>
                                    <value name="A">
                                      <shadow type="math_number" id="-vsQMn{upKtMDoI`L}$;">
                                        <field name="NUM">1</field>
                                      </shadow>
                                      <block type="variables_get" id="L:q!KNR)=deK@OB.]k9U">
                                        <field name="VAR" id="R%;fDF9FEPFO~TudO}Lx" variabletype="">k</field>
                                      </block>
                                    </value>
                                    <value name="B">
                                      <shadow type="math_number" id="*za;DcGPZ=@ULlL811q1">
                                        <field name="NUM">1</field>
                                      </shadow>
                                      <block type="math_arithmetic" id="`AxxFYu~Yg~:FsNZmP+-">
                                        <field name="OP">MULTIPLY</field>
                                        <value name="A">
                                          <shadow type="math_number" id="tV8dUulCyr*fqy1EI!Xq">
                                            <field name="NUM">1</field>
                                          </shadow>
                                          <block type="variables_get" id="cvo!5OkNUeh1RKC},}VW">
                                            <field name="VAR" id="R%;fDF9FEPFO~TudO}Lx" variabletype="">k</field>
                                          </block>
                                        </value>
                                        <value name="B">
                                          <shadow type="math_number" id="}99o_-=ycota;0Z1P1~R">
                                            <field name="NUM">1</field>
                                          </shadow>
                                          <block type="variables_get" id=",+^3(%n{SeH(T[kIPHA8">
                                            <field name="VAR" id="R%;fDF9FEPFO~TudO}Lx" variabletype="">k</field>
                                          </block>
                                        </value>
                                      </block>
                                    </value>
                                  </block>
                                </value>
                                <value name="B">
                                  <shadow type="math_number" id="Gu8*|+%RMJFfLIi@D,w4">
                                    <field name="NUM">1</field>
                                  </shadow>
                                  <block type="math_arithmetic" id="+mdAba)06=IxRYhE|k($">
                                    <field name="OP">MULTIPLY</field>
                                    <value name="A">
                                      <shadow type="math_number" id="V*5I282LmY,ksFFEPrr5">
                                        <field name="NUM">1</field>
                                      </shadow>
                                      <block type="variables_get" id="H)]T7Mj;O]e=}P=aQ6W=">
                                        <field name="VAR" id=":Q*89vms0)XU]voU=IvC" variabletype="">h</field>
                                      </block>
                                    </value>
                                    <value name="B">
                                      <shadow type="math_number" id="*za;DcGPZ=@ULlL811q1">
                                        <field name="NUM">1</field>
                                      </shadow>
                                      <block type="math_arithmetic" id="kJ+hmr(gQ7CGkeHp]Jgw">
                                        <field name="OP">MULTIPLY</field>
                                        <value name="A">
                                          <shadow type="math_number" id="/=?g.OE/lK?_toq2;EXr">
                                            <field name="NUM">1</field>
                                          </shadow>
                                          <block type="variables_get" id="};@YzD%Lr73D:;p*UL7K">
                                            <field name="VAR" id=":Q*89vms0)XU]voU=IvC" variabletype="">h</field>
                                          </block>
                                        </value>
                                        <value name="B">
                                          <shadow type="math_number" id="nu7}jxI!yoqY*H]fLsBV">
                                            <field name="NUM">1</field>
                                          </shadow>
                                          <block type="variables_get" id="_*dGEzkAk5:cM[d8Kskq">
                                            <field name="VAR" id=":Q*89vms0)XU]voU=IvC" variabletype="">h</field>
                                          </block>
                                        </value>
                                      </block>
                                    </value>
                                  </block>
                                </value>
                              </block>
                            </value>
                            <value name="B">
                              <shadow type="math_number" id="s7}o{jl?Zd5~PZ^na?7F">
                                <field name="NUM">1</field>
                              </shadow>
                              <block type="math_arithmetic" id="_ve.e5Dmz?dn)n^LW-L|">
                                <field name="OP">MULTIPLY</field>
                                <value name="A">
                                  <shadow type="math_number" id="ytu/6YP.*8WXV?9%.(w!">
                                    <field name="NUM">1</field>
                                  </shadow>
                                  <block type="variables_get" id="szfW/O6fxyJill6Bitip">
                                    <field name="VAR" id="t^LNI[nk(Zv@KGPO5OY|" variabletype="">m</field>
                                  </block>
                                </value>
                                <value name="B">
                                  <shadow type="math_number" id="*za;DcGPZ=@ULlL811q1">
                                    <field name="NUM">1</field>
                                  </shadow>
                                  <block type="math_arithmetic" id="Vt$0n$fNep~j?HVun;Z+">
                                    <field name="OP">MULTIPLY</field>
                                    <value name="A">
                                      <shadow type="math_number" id="9`TH6aA;[9Z48}K}?k6S">
                                        <field name="NUM">1</field>
                                      </shadow>
                                      <block type="variables_get" id="k=(;bp*=;*xhVDqKz#mE">
                                        <field name="VAR" id="t^LNI[nk(Zv@KGPO5OY|" variabletype="">m</field>
                                      </block>
                                    </value>
                                    <value name="B">
                                      <shadow type="math_number" id="A|`s`}KSFLj]JI=BLHt]">
                                        <field name="NUM">1</field>
                                      </shadow>
                                      <block type="variables_get" id="P7~W7xTUiLEqn]0b;4bE">
                                        <field name="VAR" id="t^LNI[nk(Zv@KGPO5OY|" variabletype="">m</field>
                                      </block>
                                    </value>
                                  </block>
                                </value>
                              </block>
                            </value>
                          </block>
                        </value>
                        <value name="B">
                          <block type="variables_get" id="D!N*Q:*a`pG^|kUYXdRG">
                            <field name="VAR" id="KrWg%,}}HyVOBG=_~^*/" variabletype="">n</field>
                          </block>
                        </value>
                      </block>
                    </value>
                    <statement name="DO0">
                      <block type="text_print" id="N:n/ybvVaaT;.lB4vSiN">
                        <value name="TEXT">
                          <shadow type="text" id="Cj6Er|k)c4~s^B=ql0@a">
                            <field name="TEXT">abc</field>
                          </shadow>
                          <block type="text" id="n[_6^cqT*_nH1rmC:eH-">
                            <field name="TEXT">不是水仙花数</field>
                          </block>
                        </value>
                      </block>
                    </statement>
                    <statement name="ELSE">
                      <block type="text_print" id="bG(A|{k$x7hWvk@d9iQ.">
                        <value name="TEXT">
                          <shadow type="text" id="Cj6Er|k)c4~s^B=ql0@a">
                            <field name="TEXT">abc</field>
                          </shadow>
                          <block type="text" id="F;A@`*QV`pD_H+?4GBn*">
                            <field name="TEXT">是水仙花数</field>
                          </block>
                        </value>
                      </block>
                    </statement>
                  </block>
                </next>
              </block>
            </next>
          </block>
        </next>
      </block>
    </next>
  </block>
</xml>














