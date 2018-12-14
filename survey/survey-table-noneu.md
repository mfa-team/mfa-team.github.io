---
layout: full-page
title: Survey on MFA implementations for online banking services
---

<h2>Non-EU Banks</h2>

<table style="color: black;">
	<thead style="font-weight: bold; font-size: 14pt;">
		<td>Bank name</td>
		<td>Country</td>
		<td>Enr.</td>
		<td>Authenticators</td>
		<td>Binding</td>
		<td>IPs</td>
		<td>MPs</td>
		<td>Ex.</td>
	</thead>
	<tr class="bank-row" id="icbc">
		<td><a href="banks/cn/icbc">ICBC</a></td>
		<td>CN</td>
		<td> <i class="fas fa-university"></i> </td>
		<td> \begin{tabular}{c} \auth{\aR}{}{O,K} \chanout{\otp}{h} <br/> \chanin{\opid}{i}  \auth{\aR}{\ask}{O} \chanout{\otp}{i} <br/> \aM <br/> \chanin{\otp}{m} \aS$^{\!\!\textnormal{\scalebox{1}{{\ask}}}}$ \chanout{\otp}{h}\end{tabular} </td>
		<td> \begin{tabular}{c} <i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> \end{tabular} </td>
		<td> \begin{tabular}{c} IP-2 <br/> IP-3 <br/> IP-11 <br/> IP-15 \end{tabular}  </td>
		<td> \begin{tabular}{c} MP-2 <br/> MP-6 <br/> MP-10 \end{tabular} </td>
		<td> \singleck </td>
	</tr>
	<tr class="bank-row" id="ccb">
		<td><a href="banks/cn/ccb">CCB</a></td>
		<td>CN</td>
		<td><i class="fas fa-university"></i></td>
		<td>\begin{tabular}{c} \chanin{\opid}{h} \auth{\aR}{\ask}{O,K} \chanout{\otp}{h} <br/> \aM <br/> \chanin{\otp}{m} \aS$^{\!\!\textnormal{\scalebox{1}{{\ask}}}}$ \chanout{\otp}{h} \end{tabular} </td>
		<td>\begin{tabular}{c} <i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i>  \end{tabular} </td>
		<td>\begin{tabular}{c}IP-3 <br/> IP-11 <br/> IP-15 \end{tabular} </td>
		<td>\begin{tabular}{c} MP-6 <br/> MP-10 <br/> MP-13 \end{tabular} </td>
		<td>\singleck</td>
	</tr>
	<tr class="bank-row" id="abc">
		<td><a href="banks/cn/abc">ABC</a></td>
		<td>CN</td>
		<td><i class="fas fa-university"></i></td>
		<td>\begin{tabular}{c} \chanin{\opid}{h} \auth{\aR}{}{O,K} \chanout{\otp}{h} <br/> \chanin{\opid}{i}  \auth{\aR}{\ask}{O} \chanout{\otp}{i}  <br/> \aM <br/> \aK  \end{tabular} </td>
		<td>\begin{tabular}{c} <bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i>  <br/><i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-globe-americas"></i><br/> <bold>E</bold>, <i class="fas fa-university"></i>, -- \end{tabular} </td>
		<td>\begin{tabular}{c} IP-4 <br/> IP-9 <br/> IP-12 \end{tabular} </td>
		<td>\begin{tabular}{c} MP-4 <br/> MP-7 <br/> MP-11 \end{tabular}</td>
		<td>\singleck</td>
	</tr>
	<tr class="bank-row" id="chase">
		<td><a href="banks/us/chase">Chase</a></td>
		<td>USA</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td>\chanin{\otp}{m} \aS{} \chanout{\otp}{h} </td>
		<td><bold>E</bold>, <i class="fas fa-globe-americas"></i> , <i class="fas fa-globe-americas"></i>  </td>
		<td>IP-14 </td>
		<td></td>
		<td>\doubleck{}</td>
	</tr>
	<tr class="bank-row" id="bank-of-america">
		<td>><a href="banks/us/bank-of-america">Bank of America</a></td>
		<td>USA</td>
		<td><i class="fas fa-globe-americas"></i></td>
		<td>\chanin{\otp}{m} \aS{} \chanout{\otp}{h} </td>
		<td><bold>E</bold>, <i class="fas fa-globe-americas"></i> , <i class="fas fa-globe-americas"></i>  </td>
		<td>IP-14 </td>
		<td></td>
		<td>\doubleck{}</td>
	</tr>
	<tr class="bank-row" id="wells-fargo">
		<td>><a href="banks/us/wells-fargo">Wells Fargo</a></td>
		<td>USA</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td>\chanin{\otp}{m} \aS{} \chanout{\otp}{h} </td>
		<td><bold>E</bold>, <i class="fas fa-globe-americas"></i> , <i class="fas fa-globe-americas"></i>  </td>
		<td>IP-14</td>
		<td></td>
		<td>\doubleck{}</td>
	</tr>
	<tr class="bank-row" id="ubs">
		<td>><a href="banks/ch/ubs">UBS</a></td>
		<td>CH</td>
		<td><i class="fas fa-globe-americas"></i></td>
		<td>\chanin{\opid}{h} \auth{\aR}{}{O,K} \chanout{\otp}{h} <br/> \chanin{\opid}{h} \auth{\aR}{}{O,K} \chanout{\otp}{h} <br/> \chanin{\opid}{i} \auth{\aR}{\ask}{O} \chanout{\otp}{i} <br/> \auth{\aA}{}{I} <br/>	\chanin{\opid}{o} \auth{\aA}{\ask}{O,K} \chanout{\otp}{h} <br/>
		\chanin{\opid}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i} <br/> </td>
		<td> <bold>E</bold>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, -- <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/></td>
		<td> IP-3 <br/> IP-8 <br/> IP-8 <br/> IP-22 </td>
		<td> MP-3 <br/> MP-3 <br/> MP-20 <br/> MP-28 </td>
		<td> \doubleck{}</td>
	</tr>
	<tr class="bank-row" id="credit-suisse">
		<td><a href="banks/ch/credit-suisse">Credit Suisse</a></td>
		<td>CH</td>
		<td><i class="fas fa-globe-americas"></i></td>
		<td>\auth{\aR}{}{O} \chanout{\otp}{h} <br/> \chanin{\otp}{m} \aS{} \chanout{\otp}{h}<br/> \chanin{\opid}{o} \auth{\aA}{}{O,K} \chanout{\otp}{h} <br/> \chanin{\opid}{i} \auth{\aA}{}{O,K} \chanout{\otp}{i} </td>
		<td><bold>E</bold>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> <bold>E</bold>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> 	</td>
		<td>IP-1 <br/> IP-14  <br/> IP-22</td>
		<td>MP-18</td>
		<td>\doubleck{}</td>
	</tr>
	<tr class="bank-row" id="raiffeisen">
		<td><a href="banks/ch/raiffeisen">Raiffeisen</a></td>
		<td>CH</td>
		<td><i class="fas fa-globe-americas"></i></td>
		<td>\aM <br/> \chanin{\opid}{o} \auth{\aR}{\ask}{O} \chanout{otp}{h} <br/> \chanin{\otp}{m} \aS{} \chanout{\otp}{h} <br/> \chanin{\opid}{o} \auth{\aA}{\ask}{O,K} \chanout{\otp}{h} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i} \end{tabular}  </td> 
		<td> <bold>E</bold>, <i class="fas fa-globe-americas"></i> , <i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <bold>E</bold>, <i class="fas fa-globe-americas"></i> , <i class="fas fa-globe-americas"></i> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
		<td>IP-6<br/> IP-11 <br/> IP-14n<br/> IP-23 </td>
		<td>MP-12 <br/> MP-20 </td>
		<td> \faRemove{} </td>
	</tr>