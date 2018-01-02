# 1.小组个人xml代码
## 1.1李曦云
<xml xmlns="http://www.w3.org/1999/xhtml">
  <variables>
    <variable type="" id="s^SLc[BXRk;+CY4Q{qOy">n</variable>
    <variable type="" id="!{ZCj+n6!#(MtgK,Erz4">a</variable>
    <variable type="" id="M[4Rf`Pb!@Q|cNU@(d)G">b</variable>
    <variable type="" id="?*u}Dbu37_][00F*5sFM">t</variable>
    <variable type="" id="9gtCx#rph1o$6obFm?rL">flag</variable>
    <variable type="" id="(`pS#Ibn|#+Mm}
    1Ba8bT">e</variable>
    <variable type="" id="P{j9v_6c:b,_=Ez;i6DZ">s1</variable>
    <variable type="" id=".6OL^]/8h(sF3~sS6l4n">s2</variable>
    <variable type="" id="L:gJnfpoyhH:=71oT34)">time</variable>
  </variables>
  <block type="text_print" id="R`}sUc;pfwDe+~.VX{?)" x="88" y="38">
    <value name="TEXT">
      <shadow type="text" id="$:?i@5:^z_QhHvuG#fh4">
        <field name="TEXT">欢迎来到猜数字游戏，按1为单人挑战模式，0为游戏退出，2为游戏说明，4为双人对战模式，难度可以通过5修改</field>
      </shadow>
    </value>
    <next>
      <block type="variables_set" id=";?-Kgds|9u$KKRrb^S^J">
        <field name="VAR" id="!{ZCj+n6!#(MtgK,Erz4" variabletype="">a</field>
        <value name="VALUE">
          <block type="text_prompt_ext" id="+@t}P^CrODWV(*TFw;J5">
            <mutation type="TEXT"></mutation>
            <field name="TYPE">TEXT</field>
            <value name="TEXT">
              <shadow type="text" id="4IxgQ|7aDy@xd8XD26w`">
                <field name="TEXT">请根据上述提示输入</field>
              </shadow>
            </value>
          </block>
        </value>
        <next>
          <block type="variables_set" id="ZHE!L4*t8)!{ACrt[1gj">
            <field name="VAR" id="?*u}Dbu37_][00F*5sFM" variabletype="">t</field>
            <value name="VALUE">
              <block type="math_number" id=",fq^pF}W7t]Z_y/Mi:65">
                              <field name="NUM">0</field>
              </block>
            </value>
            <next>
              <block type="variables_set" id="Kz,K-Ixwh:`Izm^!po#W">
                <field name="VAR" id="9gtCx#rph1o$6obFm?rL" variabletype="">flag</field>
                <value name="VALUE">
                  <block type="math_number" id="14QPwZxZYvs4ov9+b*/;">
                    <field name="NUM">0</field>