
<SCRIPT>
function compute(obj) 
{obj.expr.value = eval(obj.expr.value)}
var one = '1'
var two = '2'
var three = '3'
var four = '4'
var five = '5'
var six = '6'
var seven = '7'
var eight = '8'
var nine = '9'
var zero = '0'
var plus = '+'
var minus = '-'
var multiply = '*'
var divide = '/'
var decimal = '.'
function enter(obj, string) 
{obj.expr.value += string}
function clear(obj) 
{obj.expr.value = ''}
</SCRIPT>
					 <FONT COLOR="#CC0000" face="Arial"><P><B>الألة الحاسبة 
الإلكترونية</B></P></FONT>
						<FORM name="calc">
<DIV align="center">
					 <TABLE border="1" bgcolor="#0033CC">
<TR>
<TD colSpan="4"><INPUT size=30 
name=expr action="compute(this.form)"></TD></TR>
<TR>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, seven)" type=button value=" 7 "></P></TD>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, eight)" type=button value=" 8 "></P></TD>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, nine)" type=button value=" 9 "></P></TD>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, divide)" type=button value=" / "></P></TD></TR>
<TR>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, four)" type=button value=" 4 "></P></TD>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, five)" type=button value=" 5 "></P></TD>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, six)" type=button value=" 6 "></P></TD>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, multiply)" type=button value=" * "></P></TD></TR>
<TR>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, one)" type=button value=" 1 "></P></TD>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, two)" type=button value=" 2 "></P></TD>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, three)" type=button value=" 3 "></P></TD>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, minus)" type=button value=" - "></P></TD></TR>
<TR>
<TD bgColor="#000033" colSpan=2>
<P><INPUT onclick="enter(this.form, zero)" type=button value=" 0 "></P></TD>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, decimal)" type=button value=" . "></P></TD>
<TD bgColor="#000033">
<P><INPUT onclick="enter(this.form, plus)" type=button value=" + "></P></TD></TR>
<TR>
<TD bgColor="#000033" colSpan=2>
<P><INPUT onclick=compute(this.form) type=button value=" = "></P></TD>
<TD bgColor="#000033" colSpan=2>
<P><INPUT onclick=clear(this.form) type=reset value=AC>
							 </P></TD></TR></TABLE></DIV></FORM>
							 <P align="center">
<FONT face="Courier , New tahoma , erdana, arial, helveticav" size="2"
color="#0000FF"><B><A target="_blank" href="http://www.amrsalama.com" style="TEXT-DECORATION: NONE">BY amr salama</A></B></FONT>
>


