<table>
	<th>
		<td>Bank name</td>
		<td>Country</td>
		<td>Enrollment</td>
		<td>Authenticators</td>
		<td>Binding</td>
		<td>IPs</td>
		<td>MPs</td>
		<td>Exemptions</td>
	</th>
	<tr class="bank-row" id="deutsche-bank">
		<td><a href="banks/de/deutsche-bank">Deutsche Bank</a> 	</td>
		<td> DE	</td>
		<td> <i class="fas fa-university"></i> </td>
		<td> \auth{\aA}{}{I} <br/> \chanin{\opid}{o} \auth{\aR}{\ask}{O} \chanout{\otp}{h} <br/> \aM <br/> \aS$^{\!\!\textnormal{\scalebox{1}{{\ask}}}}$ <br/> \chanin{\opid}{o} \auth{\aA}{\ask}{O} \chanout{\otp}{h} <br/></td>
		<td> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,-- <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-university"></i>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(\aS)</td>
		<td>  IP-6 <br/> IP-11 <br/> IP-15 <br/> IP-21  </td>
		<td>  MP-10 <br/> MP-19 <br/> MP-25 <br/> MP-27  </td>
		<td> <i class="fas fa-check"></i> </td>
	</tr>
	<tr class="bank-row" id="vr-bank">
		<td><a href="banks/de/vr-bank">VR Bank</a> </td>
		<td> DE	</td>
		<td><i class="fas fa-university"></i> </td>
		<td>\auth{\aA}{}{I} <br/> \chanin{\opid}{o} \auth{\aR}{\ask}{O} \chanout{\otp}{h} <br/> \chanin{\otp}{m} \aS$^{\!\!\textnormal{\scalebox{1}{{\ask}}}}$ \chanout{\otp}{h} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i} <br/> \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,K} \chanout{\otp}{n} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,I} \chanout{\otp}{i} <br/> \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,I} \chanout{\otp}{n} </td>
		<td><i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>, <img src="/res/img/binding/mfa_icon.png" height=20 />  <br/> <i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-globe-americas"></i> <br/>  <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> </td>
		<td>	IP-6 <br/> IP-15 <br/> IP-31 <br/> IP-32 </td>
		<td> 	MP-8 <br/> MP-20,<br/> MP-21 <br/> MP-22,<br/>MP-28 <br/> MP-29	</td>
		<td> <i class="fas fa-check"></i> </td>
	</tr>
	<tr class="bank-row" id="commerzbank">
		<td><a href="banks/de/commerzbank">Commerzbank</a>  </td>
		<td>DE   </td>
		<td><i class="fas fa-globe-americas"></i> </td><td> \auth{\aA}{}{I} <br/> \chanin{\opid{}}{o} \auth{\aR}{\ask}{O} \chanout{\otp{}}{h} <br/> \aM <br/> \chanin{\otp{}}{m} \aS$^{\!\!\textnormal{\scalebox{1}{{\ask}}}}$ \chanout{\otp{}}{h} <br/> \chanin{\opid{}}{o} \auth{\aA}{\ask}{O} \chanout{\otp{}}{h} <br/> \chanin{\opid{}}{i} \auth{\aA}{\ask}{O} \chanout{\otp{}}{i} </td>
		<td><i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, -- <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>  <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(\bS) <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(\bS) </td>
		<td>  IP-6 <br/> IP-11 <br/> IP-15 <br/> IP-21  </td>
		<td>  MP-8 <br/> MP-19 <br/> MP-22 <br/> MP-27  </td>
		<td> <i class="fas fa-check"></i> </td>
	</tr>
	<tr class="bank-row" id="hsbc">
		<td><a href="banks/uk/hsbc">HSBC</a></td>
		<td>UK	</td>
		<td><i class="fas fa-university"></i>  </td>
		<td>\auth{\aR}{}{O,K} \chanout{\otp{}}{h} <br/> \auth{\aA}{}{O,K} \chanout{\otp{}}{h} <br/> \auth{\aA}{}{O,I} \chanout{\otp{}}{h} <br/> \auth{\aA}{}{O,K} \chanout{\otp{}}{i} <br/> \auth{\aA}{}{O,I} \chanout{\otp{}}{i} </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA </td>
		<td> IP-2 <br/> IP-19 <br/> IP-20  </td>
		<td> MP-15 <br/> MP-16 </td>
		<td> <i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="barclays">
		<td><a href="banks/uk/barclays">Barclays</a></td>
		<td>UK	</td>
		<td> <i class="fas fa-university"></i>  </td>
		<td>\aK <br/> \auth{\aR}{}{O,K} \chanout{\otp{}}{h} <br/> \auth{\aA}{}{O,K} \chanout{\otp{}}{h} <br/> \auth{\aA}{}{O,I} \chanout{\otp{}}{h}  </td>
		<td><bold>E</bold>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i><br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, \bMFA  <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, \bMFA </td>
		<td> IP-2 <br/> IP-19, <br/> IP-20 </td>
		<td></td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="lloyds-bank">
		<td><a href="banks/uk/lloyds-bank">LLoyds Bank</a></td>
		<td>UK</td>
		<td><i class="fas fa-university"></i>   </td>
		<td>\aK <br/> \chanin{\otp{}}{h} \aS{} \chanout{\otp}{m} <br/> \chanin{\opid{}}{n} \auth{\aOOBS}{}{O,K} \chanout{\otp{}}{n} <br/> \chanin{\opid{}}{n} \auth{\aOOBS}{}{O,I} \chanout{\otp{}}{n} <br/> \auth{\aA}{}{I} <br/> \chanin{\opid}{i} \auth{\aA}{}{O} \chanout{otp}{i}  </td>
		<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> </td>
		<td> IP-17 <br/> IP-29, <br/> IP-30 </td>
		<td>MP-17 <br/> MP-26 </td>
		<td> <i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="bnp-paribas">
		<td><a href="banks/fr/bnp-paribas">BNP Paribas</a></td>
		<td>FR </td>
		<td><i class="fas fa-globe-americas"></i>   </td>
		<td>\chanin{\otp}{m} \aS{} \chanout{\otp}{h}<br/> \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,K} \chanout{\otp}{n} <br/> \chanin{\otp}{i} \auth{\aA}{}{O} \chanout{\otp}{i}  </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(\aS) <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(\aS)  </td>
		<td> IP-14 <br/> IP-27 </td>
		<td>MP-12,MP-20 </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="credit-agricole">
		<td><a href="banks/fr/credit-agricole">Credit Agricole</a></td>
		<td>FR </td>
		<td> <i class="fas fa-globe-americas"></i>  </td>
		<td>\chanin{\otp{}}{m} \aS{} \chanout{\otp}{h} </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> </td>
		<td>IP-14 </td>
		<td> </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="societe-generale">
		<td><a href="banks/fr/societe-generale">Societe Generale</a></td>
		<td>FR </td>
		<td><i class="fas fa-globe-americas"></i>   </td>
		<td>\chanin{\otp{}}{m} \aS{} \chanout{\otp}{h} <br/> \chanin{\opid{}}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i} <br/> \chanin{\opid{}}{n} \auth{\aOOBS}{\ask}{O,K} \chanout{\otp}{n}  </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(\aS) <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(\aS) </td>
		<td> IP-14 <br/> IP-27</td>
		<td> MP-20 </td>
		<td><i class="fas fa-check"></i></td>
	</tr>
	<tr class="bank-row" id="unicredit">
		<td><a href="banks/it/unicredit">Unicredit</a></td>
		<td>IT </td>
		<td><i class="fas fa-university"></i>   </td>
		<td>\auth{\aR}{}{O} \chanout{\otp{}}{h} <br/> \aM <br/> \chanin{\opid}{h} \auth{\aA}{\ask}{O,K} \chanout{\otp}{h} <br/> \chanin{\opid}{h} \auth{\aA}{\ask}{O,I} \chanout{\otp}{h} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i} </td>
		<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA </td>
		<td>  IP-1 <br/> IP-11, <br/> IP-24 <br/> IP-25  </td>
		<td> MP-20 <br/> MP-21 </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="banca-intesa">
		<td><a href="banks/it/banca-intesa">Banca Intesa</a></td>
		<td>IT </td>
		<td><i class="fas fa-university"></i>   </td>
		<td>\auth{\aR}{}{O} \chanout{\otp{}}{h} <br/> \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,K} \chanout{\otp}{n}<br/>  \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,I} \chanout{\otp}{n} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,I} \chanout{\otp}{i}  </td>
		<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, \bMFA <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, \bMFA <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, \bMFA <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, \bMFA </td>
		<td> IP-1 <br/> IP-27, <br/> IP-28  </td>
		<td> MP-1 <br/> MP-20, <br/> MP-21  </td>
		<td><i class="fas fa-check-double"></i> </td>
	</tr>
	<tr class="bank-row" id="banco-bpm">
		<td><a href="banks/it/banco-bpm">Banco BPM</a></td>
		<td>IT </td>
		<td><i class="fas fa-university"></i>   </td>
		<td>\auth{\aR}{}{O} \chanout{\otp}{h} <br/> \auth{\aR}{}{O,K} \chanout{\otp}{h} <br/>  \auth{\aA{}}{}{O} \chanout{\otp}{h}<br/> \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,K} \chanout{\otp}{n} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,K}  \chanout{\otp}{i} </td>
		<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA  </td>
		<td>IP-1 <br/> IP-2, <br/> IP-18 <br/> IP-27  </td>
		<td>MP-1 <br/> MP-20 </td>
		<td><i class="fas fa-check"></i> </td>
	</tr>
	<tr class="bank-row" id="banco-santander">
		<td><a href="banks/es/banco-santander">Banco Santander</a></td>
		<td>ES	</td>
		<td><i class="fas fa-globe-americas"></i>   </td>
		<td>\aK <br/> \chanin{\otp}{m} \aS{} \chanout{\otp}{h}  </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>  </td>
		<td>IP-16</td>
		<td>MP-14 </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="bbva">
		<td><a href="banks/es/bbva">BBVA</a></td>
		<td>ES</td>
		<td><i class="fas fa-globe-americas"></i></td>
		<td>\chanin{\otp}{m} \aS$^{\!\!\textnormal{\scalebox{1}{{\ask}}}}$ \chanout{\otp}{h} </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>  </td>
		<td>IP-15 </td>
		<td>MP-13 </td>
		<td><i class="fas fa-check"></i></td>
	</tr>
	<tr class="bank-row" id="la-caixa">
		<td><a href="banks/es/la-caixa">La Caixa</a></td>
		<td>ES </td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td>\aM <br/> \chanin{\opid}{n} \auth{\aOOBS{}}{\ask}{O} \chanout{\otp}{n} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O} \chanout{\otp}{i} </td>
		<td><bold>E</bold>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, \bMFA <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, \bMFA  </td>
		<td>IP-11<br/> IP-26 </td>
		<td>MP-19</td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="ing">
		<td><a href="banks/nl/ing">ING</a></td>
		<td>NL	</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td>\aM <br/> \chanin{\otp}{m} \aS$^{\!\!\textnormal{\scalebox{1}{{\ask}}}}$ \chanout{\otp}{h} <br/> \chanin{\opid}{n}\auth{\aOOBS{}}{\ask}{O,K} \chanout{\otp}{n} <br/> \auth{\aA}{}{I} <br/> \chanin{\opid}{i} \auth{\aA{}}{\ask}{O} \chanout{\otp}{i} </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(\aS) <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, -- <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(\aS) </td>
		<td> IP-11 <br/> IP-15, <br/> IP-27  </td>
		<td>MP-19 <br/> MP-27 </td>
		<td><i class="fas fa-check"></i></td>
	</tr>
	<tr class="bank-row" id="rabobank">
		<td><a href="banks/nl/rabobank">Rabobank</a></td>
		<td>NL	</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td>\chanin{\opid}{o} \auth{\aR}{\ask}{O,K} \chanout{\otp}{h} <br/> \chanin{\opid}{h} \auth{\aR}{\ask}{O,K} \chanout{\otp}{h} <br/> \auth{\aA}{}{I}  </td>
		<td><bold>E</bold>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> -- <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, --  </td>
		<td>IP-7 <br/> IP-10 </td>
		<td>MP-9 <br/> MP-24 </td>
		<td> <i class="fas fa-check-double"></i> </td>
	</tr>
	<tr class="bank-row" id="abn-amro">
		<td><a href="banks/nl/abn-amro">ABN AMRO</a></td>
		<td>NL	</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td>\chanin{\opid}{i} \auth{\aR}{\ask}{O,K} \chanout{\otp}{i} <br/> \chanin{\opid}{h} \auth{\aR}{\ask}{O,K} \chanout{\otp}{h} <br/> \auth{\aA}{}{I}  </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> -- <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, --<br/>  </td>
		<td>IP-5 <br/> IP-10 </td>
		<td> MP-5 <br/> MP-5, <br/> MP-23 <br/> MP-23  </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="nordea">
		<td><a href="banks/sw/nordea">Nordea</a></td>
		<td>SW	</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td>\chanin{\opid}{h} \auth{\aR}{}{O,K} \chanout{\otp}{h} <br/> \chanin{\opid}{i} \auth{\aR}{\ask}{O,K} \chanout{\otp}{i} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i} <br/> \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,K} \chanout{\otp}{n}<br/> \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,I} \chanout{\otp}{n} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i}<br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,I} \chanout{\otp}{i} </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA </td>
		<td> IP-5 <br/> IP-8, <br/> IP-13 <br/> IP-27, <br/> IP-28  </td>
		<td> MP-3 <br/> MP-20, <br/>MP-21  </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="svenska-handelsbanken">
		<td><a href="banks/sw/svenska-handelsbanken">Svenska Handelsbanken</a></td>
		<td>SW	</td>
		<td><i class="fas fa-university"></i> </td>
		<td>\aM <br/> \chanin{\opid}{h} \auth{\aR}{}{O,K} \chanout{\otp}{h} <br/> \chanin{\opid}{i} \auth{\aR}{\ask}{O,K} \chanout{\otp}{i} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i} <br/> \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,K} \chanout{\otp}{n}<br/> \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,I} \chanout{\otp}{n} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i}<br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,I} \chanout{\otp}{i}  </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> \bMFA,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> \bMFA,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA  </td>
		<td> IP-5 <br/> IP-8, <br/> IP-11 <br/> IP-13,<br/>IP-27 <br/> IP-28 </td>
		<td> MP-3 <br/> MP-10, <br/> MP-20 <br/> MP-21 </td>
		<td><i class="fas fa-times"></i></td>
	</tr>
	<tr class="bank-row" id="seb">
		<td><a href="banks/sw/seb">SEB</a></td>
		<td>SW	</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td>\chanin{\opid}{h} \auth{\aR}{}{O,K} \chanout{\otp}{h} <br/> \chanin{\opid}{i} \auth{\aR}{\ask}{O,K} \chanout{\otp}{i} <br/> \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,K} \chanout{\otp}{n}<br/> \chanin{\opid}{n} \auth{\aOOBS}{\ask}{O,I} \chanout{\otp}{n} <br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,K} \chanout{\otp}{i}<br/> \chanin{\opid}{i} \auth{\aA}{\ask}{O,I} \chanout{\otp}{i} </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> \bMFA,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,\bMFA </td>
		<td> IP-5 <br/> IP-8,<br/> IP-27 <br/> IP-28 </td>
		<td> MP-3 <br/> MP-20, <br/> MP-21 </td>
		<td> <i class="fas fa-times"></i></td>
	</tr>
</table>
