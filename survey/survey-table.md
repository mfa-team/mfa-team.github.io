---
layout: full-page
title: Survey on MFA implementations for online banking services
---


<table style="color: black;">
	<thead style="font-weight: bold; font-size: 14pt;">
		<td>Bank name</td>
		<td>Country</td>
		<td>Enrollment</td>
		<td>Authenticators</td>
		<td>Binding</td>
		<td>IPs</td>
		<td>MPs</td>
		<td>Exemptions</td>
	</thead>
	<tr class="bank-row" id="deutsche-bank">
		<td><a href="banks/de/deutsche-bank">Deutsche Bank</a> 	</td>
		<td> DE	</td>
		<td> <i class="fas fa-university"></i> </td>
		<td> \auth{\aA}{}{I} <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> \auth{<i class="fas fa-calculator"></i>}{<sup class="authr-info">?</sup>}{O} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <i class="fas fa-table"></i> <br/> <i class="fas fa-sim-card"></i>$^{\!\!\textnormal{\scalebox{1}{{<sup class="authr-info">?</sup>}}}}$ <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/></td>
		<td> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,-- <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-university"></i>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>)</td>
		<td>  IP-6 <br/> IP-11 <br/> IP-15 <br/> IP-21  </td>
		<td>  MP-10 <br/> MP-19 <br/> MP-25 <br/> MP-27  </td>
		<td> <i class="fas fa-check"></i> </td>
	</tr>
	<tr class="bank-row" id="vr-bank">
		<td><a href="banks/de/vr-bank">VR Bank</a> </td>
		<td> DE	</td>
		<td><i class="fas fa-university"></i> </td>
		<td>\auth{\aA}{}{I} <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> \auth{<i class="fas fa-calculator"></i>}{<sup class="authr-info">?</sup>}{O} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i>$^{\!\!\textnormal{\scalebox{1}{{<sup class="authr-info">?</sup>}}}}$ <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,I} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,I} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" />  <br/> <i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-globe-americas"></i> <br/>  <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> </td>
		<td>	IP-6 <br/> IP-15 <br/> IP-31 <br/> IP-32 </td>
		<td> 	MP-8 <br/> MP-20,<br/> MP-21 <br/> MP-22,<br/>MP-28 <br/> MP-29	</td>
		<td> <i class="fas fa-check"></i> </td>
	</tr>
	<tr class="bank-row" id="commerzbank">
		<td><a href="banks/de/commerzbank">Commerzbank</a>  </td>
		<td>DE   </td>
		<td><i class="fas fa-globe-americas"></i> </td><td> \auth{\aA}{}{I} <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> \auth{<i class="fas fa-calculator"></i>}{<sup class="authr-info">?</sup>}{O} \chanout{\otp{}}{h} <br/> <i class="fas fa-table"></i> <br/> \chanin{\otp{}}{m} <i class="fas fa-sim-card"></i>$^{\!\!\textnormal{\scalebox{1}{{<sup class="authr-info">?</sup>}}}}$ \chanout{\otp{}}{h} <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O} \chanout{\otp{}}{h} <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O} \chanout{\otp{}}{i} </td>
		<td><i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, -- <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>  <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(\bS) <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(\bS) </td>
		<td>  IP-6 <br/> IP-11 <br/> IP-15 <br/> IP-21  </td>
		<td>  MP-8 <br/> MP-19 <br/> MP-22 <br/> MP-27  </td>
		<td> <i class="fas fa-check"></i> </td>
	</tr>
	<tr class="bank-row" id="hsbc">
		<td><a href="banks/uk/hsbc">HSBC</a></td>
		<td>UK	</td>
		<td><i class="fas fa-university"></i>  </td>
		<td>\auth{<i class="fas fa-calculator"></i>}{}{O,K} \chanout{\otp{}}{h} <br/> \auth{\aA}{}{O,K} \chanout{\otp{}}{h} <br/> \auth{\aA}{}{O,I} \chanout{\otp{}}{h} <br/> \auth{\aA}{}{O,K} \chanout{\otp{}}{i} <br/> \auth{\aA}{}{O,I} \chanout{\otp{}}{i} </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
		<td> IP-2 <br/> IP-19 <br/> IP-20  </td>
		<td> MP-15 <br/> MP-16 </td>
		<td> <i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="barclays">
		<td><a href="banks/uk/barclays">Barclays</a></td>
		<td>UK	</td>
		<td> <i class="fas fa-university"></i>  </td>
		<td>\aK <br/> \auth{<i class="fas fa-calculator"></i>}{}{O,K} \chanout{\otp{}}{h} <br/> \auth{\aA}{}{O,K} \chanout{\otp{}}{h} <br/> \auth{\aA}{}{O,I} \chanout{\otp{}}{h}  </td>
		<td><bold>E</bold>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i><br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" />  <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
		<td> IP-2 <br/> IP-19, <br/> IP-20 </td>
		<td></td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="lloyds-bank">
		<td><a href="banks/uk/lloyds-bank">LLoyds Bank</a></td>
		<td>UK</td>
		<td><i class="fas fa-university"></i>   </td>
		<td>\aK <br/> \chanin{\otp{}}{h} <i class="fas fa-sim-card"></i> \chanout{\otp}{m} <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{}{O,K} \chanout{\otp{}}{n} <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{}{O,I} \chanout{\otp{}}{n} <br/> \auth{\aA}{}{I} <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{}{O} \chanout{otp}{i}  </td>
		<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> </td>
		<td> IP-17 <br/> IP-29, <br/> IP-30 </td>
		<td>MP-17 <br/> MP-26 </td>
		<td> <i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="bnp-paribas">
		<td><a href="banks/fr/bnp-paribas">BNP Paribas</a></td>
		<td>FR </td>
		<td><i class="fas fa-globe-americas"></i>   </td>
		<td><span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> \chanin{\otp}{i} \auth{\aA}{}{O} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span>  </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>)  </td>
		<td> IP-14 <br/> IP-27 </td>
		<td>MP-12,MP-20 </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="credit-agricole">
		<td><a href="banks/fr/credit-agricole">Credit Agricole</a></td>
		<td>FR </td>
		<td> <i class="fas fa-globe-americas"></i>  </td>
		<td>\chanin{\otp{}}{m} <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> </td>
		<td>IP-14 </td>
		<td> </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="societe-generale">
		<td><a href="banks/fr/societe-generale">Societe Generale</a></td>
		<td>FR </td>
		<td><i class="fas fa-globe-americas"></i>   </td>
		<td>\chanin{\otp{}}{m} <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> \chanin{\opid{}}{i} \auth{\aA}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span>  </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) </td>
		<td> IP-14 <br/> IP-27</td>
		<td> MP-20 </td>
		<td><i class="fas fa-check"></i></td>
	</tr>
	<tr class="bank-row" id="unicredit">
		<td><a href="banks/it/unicredit">Unicredit</a></td>
		<td>IT </td>
		<td><i class="fas fa-university"></i>   </td>
		<td>\auth{<i class="fas fa-calculator"></i>}{}{O} \chanout{\otp{}}{h} <br/> <i class="fas fa-table"></i> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,I} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
		<td>  IP-1 <br/> IP-11, <br/> IP-24 <br/> IP-25  </td>
		<td> MP-20 <br/> MP-21 </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="banca-intesa">
		<td><a href="banks/it/banca-intesa">Banca Intesa</a></td>
		<td>IT </td>
		<td><i class="fas fa-university"></i>   </td>
		<td>\auth{<i class="fas fa-calculator"></i>}{}{O} \chanout{\otp{}}{h} <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span><br/>  <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,I} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,I} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span>  </td>
		<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
		<td> IP-1 <br/> IP-27, <br/> IP-28  </td>
		<td> MP-1 <br/> MP-20, <br/> MP-21  </td>
		<td><i class="fas fa-check-double"></i> </td>
	</tr>
	<tr class="bank-row" id="banco-bpm">
		<td><a href="banks/it/banco-bpm">Banco BPM</a></td>
		<td>IT </td>
		<td><i class="fas fa-university"></i>   </td>
		<td>\auth{<i class="fas fa-calculator"></i>}{}{O} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> \auth{<i class="fas fa-calculator"></i>}{}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/>  \auth{\aA{}}{}{O} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,K}  <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" />  </td>
		<td>IP-1 <br/> IP-2, <br/> IP-18 <br/> IP-27  </td>
		<td>MP-1 <br/> MP-20 </td>
		<td><i class="fas fa-check"></i> </td>
	</tr>
	<tr class="bank-row" id="banco-santander">
		<td><a href="banks/es/banco-santander">Banco Santander</a></td>
		<td>ES	</td>
		<td><i class="fas fa-globe-americas"></i>   </td>
		<td>\aK <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span>  </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>  </td>
		<td>IP-16</td>
		<td>MP-14 </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="bbva">
		<td><a href="banks/es/bbva">BBVA</a></td>
		<td>ES</td>
		<td><i class="fas fa-globe-americas"></i></td>
		<td><span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i>$^{\!\!\textnormal{\scalebox{1}{{<sup class="authr-info">?</sup>}}}}$ <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>  </td>
		<td>IP-15 </td>
		<td>MP-13 </td>
		<td><i class="fas fa-check"></i></td>
	</tr>
	<tr class="bank-row" id="la-caixa">
		<td><a href="banks/es/la-caixa">La Caixa</a></td>
		<td>ES </td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td><i class="fas fa-table"></i> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS{}}{<sup class="authr-info">?</sup>}{O} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" />  </td>
		<td>IP-11<br/> IP-26 </td>
		<td>MP-19</td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="ing">
		<td><a href="banks/nl/ing">ING</a></td>
		<td>NL	</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td><i class="fas fa-table"></i> <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i>$^{\!\!\textnormal{\scalebox{1}{{<sup class="authr-info">?</sup>}}}}$ <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  />\auth{\aOOBS{}}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> \auth{\aA}{}{I} <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA{}}{<sup class="authr-info">?</sup>}{O} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, -- <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) </td>
		<td> IP-11 <br/> IP-15, <br/> IP-27  </td>
		<td>MP-19 <br/> MP-27 </td>
		<td><i class="fas fa-check"></i></td>
	</tr>
	<tr class="bank-row" id="rabobank">
		<td><a href="banks/nl/rabobank">Rabobank</a></td>
		<td>NL	</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td><span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> \auth{<i class="fas fa-calculator"></i>}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> \auth{<i class="fas fa-calculator"></i>}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> \auth{\aA}{}{I}  </td>
		<td><bold>E</bold>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> -- <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, --  </td>
		<td>IP-7 <br/> IP-10 </td>
		<td>MP-9 <br/> MP-24 </td>
		<td> <i class="fas fa-check-double"></i> </td>
	</tr>
	<tr class="bank-row" id="abn-amro">
		<td><a href="banks/nl/abn-amro">ABN AMRO</a></td>
		<td>NL	</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td><span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{<i class="fas fa-calculator"></i>}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> \auth{<i class="fas fa-calculator"></i>}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> \auth{\aA}{}{I}  </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> -- <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, --<br/>  </td>
		<td>IP-5 <br/> IP-10 </td>
		<td> MP-5 <br/> MP-5, <br/> MP-23 <br/> MP-23  </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="nordea">
		<td><a href="banks/sw/nordea">Nordea</a></td>
		<td>SW	</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td><span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> \auth{<i class="fas fa-calculator"></i>}{}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{<i class="fas fa-calculator"></i>}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,I} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,I} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
		<td> IP-5 <br/> IP-8, <br/> IP-13 <br/> IP-27, <br/> IP-28  </td>
		<td> MP-3 <br/> MP-20, <br/>MP-21  </td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="svenska-handelsbanken">
		<td><a href="banks/sw/svenska-handelsbanken">Svenska Handelsbanken</a></td>
		<td>SW	</td>
		<td><i class="fas fa-university"></i> </td>
		<td><i class="fas fa-table"></i> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> \auth{<i class="fas fa-calculator"></i>}{}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{<i class="fas fa-calculator"></i>}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,I} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,I} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span>  </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" />  </td>
		<td> IP-5 <br/> IP-8, <br/> IP-11 <br/> IP-13,<br/>IP-27 <br/> IP-28 </td>
		<td> MP-3 <br/> MP-10, <br/> MP-20 <br/> MP-21 </td>
		<td><i class="fas fa-times"></i></td>
	</tr>
	<tr class="bank-row" id="seb">
		<td><a href="banks/sw/seb">SEB</a></td>
		<td>SW	</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td><span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> \auth{<i class="fas fa-calculator"></i>}{}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{<i class="fas fa-calculator"></i>}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> \auth{\aOOBS}{<sup class="authr-info">?</sup>}{O,I} <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,K} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> \auth{\aA}{<sup class="authr-info">?</sup>}{O,I} <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
		<td> IP-5 <br/> IP-8,<br/> IP-27 <br/> IP-28 </td>
		<td> MP-3 <br/> MP-20, <br/> MP-21 </td>
		<td> <i class="fas fa-times"></i></td>
	</tr>
</table>
