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
		<td>  <i class="fas fa-calculator"></i><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  />  <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O]</span>  <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <i class="fas fa-table"></i> <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i><sup class="authr-info">?</sup> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> </td>
		<td>  <i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>  </td>
		<td>  IP-2 <br/> IP-3 <br/> IP-11 <br/> IP-15   </td>
		<td>  MP-2 <br/> MP-6 <br/> MP-10  </td>
		<td> <i class="fas fa-check"></i> </td>
	</tr>
	<tr class="bank-row" id="ccb">
		<td><a href="banks/cn/ccb">CCB</a></td>
		<td>CN</td>
		<td><i class="fas fa-university"></i></td>
		<td> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <i class="fas fa-table"></i> <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i><sup class="authr-info">?</sup> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span>  </td>
		<td> <i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i>   </td>
		<td>IP-3 <br/> IP-11 <br/> IP-15  </td>
		<td> MP-6 <br/> MP-10 <br/> MP-13  </td>
		<td><i class="fas fa-check"></i></td>
	</tr>
	<tr class="bank-row" id="abc">
		<td><a href="banks/cn/abc">ABC</a></td>
		<td>CN</td>
		<td><i class="fas fa-university"></i></td>
		<td> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <i class="fas fa-calculator"></i><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  />  <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O]</span>  <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span>  <br/> <i class="fas fa-table"></i> <br/> <img class="authr-img obj" src="res/img/authenticators/knowledge.png"  />   </td>
		<td> <bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i>  <br/><i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-globe-americas"></i><br/> <bold>E</bold>, <i class="fas fa-university"></i>, --  </td>
		<td> IP-4 <br/> IP-9 <br/> IP-12  </td>
		<td> MP-4 <br/> MP-7 <br/> MP-11 </td>
		<td><i class="fas fa-check"></i></td>
	</tr>
	<tr class="bank-row" id="chase">
		<td><a href="banks/us/chase">Chase</a></td>
		<td>USA</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td><span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>, <i class="fas fa-globe-americas"></i> , <i class="fas fa-globe-americas"></i>  </td>
		<td>IP-14 </td>
		<td></td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="bank-of-america">
		<td><a href="banks/us/bank-of-america">Bank of America</a></td>
		<td>USA</td>
		<td><i class="fas fa-globe-americas"></i></td>
		<td><span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>, <i class="fas fa-globe-americas"></i> , <i class="fas fa-globe-americas"></i>  </td>
		<td>IP-14 </td>
		<td></td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="wells-fargo">
		<td><a href="banks/us/wells-fargo">Wells Fargo</a></td>
		<td>USA</td>
		<td><i class="fas fa-globe-americas"></i> </td>
		<td><span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>, <i class="fas fa-globe-americas"></i> , <i class="fas fa-globe-americas"></i>  </td>
		<td>IP-14</td>
		<td></td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="ubs">
		<td><a href="banks/ch/ubs">UBS</a></td>
		<td>CH</td>
		<td><i class="fas fa-globe-americas"></i></td>
		<td><span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <i class="fas fa-calculator"></i><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <i class="fas fa-calculator"></i><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O]</span>  <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[I]</span>  <br/>	<span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/>
		<span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> </td>
		<td> <bold>E</bold>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, -- <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/></td>
		<td> IP-3 <br/> IP-8 <br/> IP-8 <br/> IP-22 </td>
		<td> MP-3 <br/> MP-3 <br/> MP-20 <br/> MP-28 </td>
		<td> <i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="credit-suisse">
		<td><a href="banks/ch/credit-suisse">Credit Suisse</a></td>
		<td>CH</td>
		<td><i class="fas fa-globe-americas"></i></td>
		<td><i class="fas fa-calculator"></i><span class="authr-afs">[O]</span>  <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
		<td><bold>E</bold>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> <bold>E</bold>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> 	</td>
		<td>IP-1 <br/> IP-14  <br/> IP-22</td>
		<td>MP-18</td>
		<td><i class="fas fa-check-double"></i></td>
	</tr>
	<tr class="bank-row" id="raiffeisen">
		<td><a href="banks/ch/raiffeisen">Raiffeisen</a></td>
		<td>CH</td>
		<td><i class="fas fa-globe-americas"></i></td>
		<td><i class="fas fa-table"></i> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O]</span>  <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span>   </td> 
		<td> <bold>E</bold>, <i class="fas fa-globe-americas"></i> , <i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <bold>E</bold>, <i class="fas fa-globe-americas"></i> , <i class="fas fa-globe-americas"></i> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
		<td>IP-6<br/> IP-11 <br/> IP-14<br/> IP-23 </td>
		<td>MP-12 <br/> MP-20 </td>
		<td> <i class="fas fa-times"></i> </td>
	</tr>