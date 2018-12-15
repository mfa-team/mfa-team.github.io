---
layout: full-page
title: Survey on MFA implementations for online banking services
---

In this page, an overview on the MFA implementations adopted by each bank is given, reporting the enrollment procedure, the employed authenticators and the respective binding procedures, the employed MFA protocols (both for Internet
and Mobile Payments) and the adoption of exemptions.

<h2>EU Banks</h2>

<div id="eu-banks-table-wrapper" style="overflow-x: scroll;">
	<table id="eu-banks-table" style="color: black;">
		<thead style="font-weight: bold; font-size: 12.5pt;">
			<td>Bank name</td>
			<td>C</td>
			<td>Enr.</td>
			<td>Authenticators</td>
			<td>Binding</td>
			<td>IPs</td>
			<td>MPs</td>
			<td>Ex.</td>
			<td>RLs</td>
			<td>BPs</td>
		</thead>
		<tr class="bank-row" id="deutsche-bank">
			<td><a href="banks/de/deutsche-bank">Deutsche Bank</a> 	</td>
			<td> DE	</td>
			<td> <i class="fas fa-university"></i> </td>
			<td> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[I]</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <i class="fas fa-table"></i> <br/> <i class="fas fa-sim-card"></i><sup class="authr-info">?</sup> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/></td>
			<td> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,-- <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-university"></i>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>)</td>
			<td> <a href="mfa-protocols-evaluation#IP-6"> IP-6 :<img class="mfap-pict" src="protocols-representations/pictograms/ip/IP-6.png" alt="IP-6"/> </a><br/> <a href="mfa-protocols-evaluation#IP-11">IP-11: <img class="mfap-pict" src="protocols-representations/pictograms/ip/IP-11.png" alt="IP-11"/></a> <br/> <a href="mfa-protocols-evaluation#IP-15">IP-15: <img class="mfap-pict" src="protocols-representations/pictograms/ip/IP-15.png" alt="IP-15"/></a> <br/> <a href="mfa-protocols-evaluation#IP-21">IP-21: <img class="mfap-pict" src="protocols-representations/pictograms/ip/IP-21.png" alt="IP-21"/></a> </td>
			<td> MP-10: <img class="mfap-pict" src="protocols-representations/pictograms/mp/MP-10.png" alt="MP-10"/> <br/> MP-19: <img class="mfap-pict" src="protocols-representations/pictograms/mp/MP-19.png"/><br/> MP-25: <img class="mfap-pict" src="protocols-representations/pictograms/mp/MP-25.png"/><br/> MP-27:  <img class="mfap-pict" src="protocols-representations/pictograms/mp/MP-27.png"/></td>
			<td> <i class="fas fa-check"></i> </td>
			<td><a href="requirements-evaluation#deutsche-bank">4/9</a></td>
			<td><a href="best-practices-evaluation#deutsche-bank">3/8</a></td>
		</tr>
		<tr class="bank-row" id="vr-bank">
			<td><a href="banks/de/vr-bank">VR Bank</a> </td>
			<td> DE	</td>
			<td><i class="fas fa-university"></i> </td>
			<td><img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[I]</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i><sup class="authr-info">?</sup> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> </td>
			<td><i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" />  <br/> <i class="fas fa-university"></i>, <i class="fas fa-university"></i>, <i class="fas fa-globe-americas"></i> <br/>  <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> </td>
			<td>	IP-6 <br/> IP-15 <br/> IP-31 <br/> IP-32 </td>
			<td> 	MP-8 <br/> MP-20 <br/> MP-21 <br/> MP-22 <br/>MP-28 <br/> MP-29	</td>
			<td> <i class="fas fa-check"></i> </td>
			<td><a href="requirements-evaluation#vr-bank">6/9</a></td>
			<td><a href="best-practices-evaluation#vr-bank">3/8</a></td>
		</tr>
		<tr class="bank-row" id="commerzbank">
			<td><a href="banks/de/commerzbank">Commerzbank</a></td>
			<td>DE </td>
			<td><i class="fas fa-globe-americas"></i> </td><td> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[I]</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <i class="fas fa-table"></i> <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i><sup class="authr-info">?</sup> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
			<td><i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, -- <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>  <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) </td>
			<td>  IP-6 <br/> IP-11 <br/> IP-15 <br/> IP-21  </td>
			<td>  MP-8 <br/> MP-19 <br/> MP-22 <br/> MP-27  </td>
			<td> <i class="fas fa-check"></i> </td>
			<td><a href="requirements-evaluation#commerzbank">3/9</a></td>
			<td><a href="best-practices-evaluation#commerzbank">2/8</a></td>
		</tr>
		<tr class="bank-row" id="hsbc">
			<td><a href="banks/uk/hsbc">HSBC</a></td>
			<td>UK	</td>
			<td><i class="fas fa-university"></i>  </td>
			<td><i class="fas fa-calculator"></i><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
			<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
			<td> IP-2 <br/> IP-19 <br/> IP-20  </td>
			<td> MP-15 <br/> MP-16 </td>
			<td> <i class="fas fa-check-double"></i></td>
			<td><a href="requirements-evaluation#hsbc">7/9</a></td>
			<td><a href="best-practices-evaluation#hsbc">6/8</a></td>
		</tr>
		<tr class="bank-row" id="barclays">
			<td><a href="banks/uk/barclays">Barclays</a></td>
			<td>UK	</td>
			<td> <i class="fas fa-university"></i>  </td>
			<td><img class="authr-img obj" src="res/img/authenticators/knowledge.png"  /> <br/> <i class="fas fa-calculator"></i><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span>  </td>
			<td><bold>E</bold>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i><br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" />  <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
			<td> IP-2 <br/> IP-19 <br/> IP-20 </td>
			<td></td>
			<td><i class="fas fa-check-double"></i></td>
			<td><a href="requirements-evaluation#barclays">5/9</a></td>
			<td><a href="best-practices-evaluation#barclays">5/8</a></td>
		</tr>
		<tr class="bank-row" id="lloyds-bank">
			<td><a href="banks/uk/lloyds-bank">LLoyds Bank</a></td>
			<td>UK</td>
			<td><i class="fas fa-university"></i>   </td>
			<td><img class="authr-img obj" src="res/img/authenticators/knowledge.png"  /> <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_m.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[I]</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span>  </td>
			<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> </td>
			<td> IP-17 <br/> IP-29, <br/> IP-30 </td>
			<td>MP-17 <br/> MP-26 </td>
			<td> <i class="fas fa-check-double"></i></td>
			<td><a href="requirements-evaluation#lloyds-bank">5/9</a></td>
			<td><a href="best-practices-evaluation#lloyds-bank">5/8</a></td>
		</tr>
		<tr class="bank-row" id="bnp-paribas">
			<td><a href="banks/fr/bnp-paribas">BNP Paribas</a></td>
			<td>FR </td>
			<td><i class="fas fa-globe-americas"></i>   </td>
			<td><span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span>  </td>
			<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>)  </td>
			<td> IP-14 <br/> IP-27 </td>
			<td>MP-12 <br/> MP-20 </td>
			<td><i class="fas fa-check-double"></i></td>
			<td><a href="requirements-evaluation#bnp-paribas">5/9</a></td>
			<td><a href="best-practices-evaluation#bnp-paribas">3/8</a></td>
		</tr>
		<tr class="bank-row" id="credit-agricole">
			<td><a href="banks/fr/credit-agricole">Credit Agricole</a></td>
			<td>FR </td>
			<td> <i class="fas fa-globe-americas"></i>  </td>
			<td><span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> </td>
			<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> </td>
			<td>IP-14 </td>
			<td> </td>
			<td><i class="fas fa-check-double"></i></td>
			<td><a href="requirements-evaluation#credit-agricole">4/9</a></td>
			<td><a href="best-practices-evaluation#credit-agricole">1/8</a></td>
		</tr>
		<tr class="bank-row" id="societe-generale">
			<td><a href="banks/fr/societe-generale">Societe Generale</a></td>
			<td>FR </td>
			<td><i class="fas fa-globe-americas"></i>   </td>
			<td><span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span>  </td>
			<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) </td>
			<td> IP-14 <br/> IP-27</td>
			<td> MP-20 </td>
			<td><i class="fas fa-check"></i></td>
			<td><a href="requirements-evaluation#societe-generale">5/9</a></td>
			<td><a href="best-practices-evaluation#societe-generale">3/8</a></td>
		</tr>
		<tr class="bank-row" id="unicredit">
			<td><a href="banks/it/unicredit">Unicredit</a></td>
			<td>IT </td>
			<td><i class="fas fa-university"></i>   </td>
			<td><i class="fas fa-calculator"></i><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <i class="fas fa-table"></i> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
			<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <bold>E</bold>, <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
			<td>  IP-1 <br/> IP-11 <br/> IP-24 <br/> IP-25  </td>
			<td> MP-20 <br/> MP-21 </td>
			<td><i class="fas fa-check-double"></i></td>
			<td><a href="requirements-evaluation#unicredit">5/9</a></td>
			<td><a href="best-practices-evaluation#unicredit">6/8</a></td>
		</tr>
		<tr class="bank-row" id="banca-intesa">
			<td><a href="banks/it/banca-intesa">Banca Intesa</a></td>
			<td>IT </td>
			<td><i class="fas fa-university"></i>   </td>
			<td><i class="fas fa-calculator"></i><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span><br/>  <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span>  </td>
			<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
			<td> IP-1 <br/> IP-27 <br/> IP-28  </td>
			<td> MP-1 <br/> MP-20 <br/> MP-21  </td>
			<td><i class="fas fa-check-double"></i> </td>
			<td><a href="requirements-evaluation#banca-intesa">7/9</a></td>
			<td><a href="best-practices-evaluation#banca-intesa">6/8</a></td>
		</tr>
		<tr class="bank-row" id="banco-bpm">
			<td><a href="banks/it/banco-bpm">Banco BPM</a></td>
			<td>IT </td>
			<td><i class="fas fa-university"></i>   </td>
			<td><i class="fas fa-calculator"></i><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <i class="fas fa-calculator"></i><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/>  <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span>  <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
			<td><bold>E</bold>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-university"></i>, <i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" />  </td>
			<td>IP-1 <br/> IP-2 <br/> IP-18 <br/> IP-27  </td>
			<td>MP-1 <br/> MP-20 </td>
			<td><i class="fas fa-check"></i> </td>
			<td><a href="requirements-evaluation#banco-bpm">7/9</a></td>
			<td><a href="best-practices-evaluation#banco-bpm">6/8</a></td>
		</tr>
		<tr class="bank-row" id="banco-santander">
			<td><a href="banks/es/banco-santander">Banco Santander</a></td>
			<td>ES	</td>
			<td><i class="fas fa-globe-americas"></i>   </td>
			<td><img class="authr-img obj" src="res/img/authenticators/knowledge.png"  /> <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span>  </td>
			<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>  </td>
			<td>IP-16</td>
			<td>MP-14 </td>
			<td><i class="fas fa-check-double"></i></td>
			<td><a href="requirements-evaluation#banco-santander">5/9</a></td>
			<td><a href="best-practices-evaluation#banco-santander">1/8</a></td>
		</tr>
		<tr class="bank-row" id="bbva">
			<td><a href="banks/es/bbva">BBVA</a></td>
			<td>ES</td>
			<td><i class="fas fa-globe-americas"></i></td>
			<td><span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i><sup class="authr-info">?</sup> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> </td>
			<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>  </td>
			<td>IP-15 </td>
			<td>MP-13 </td>
			<td><i class="fas fa-check"></i></td>
			<td><a href="requirements-evaluation#bbva">6/9</a></td>
			<td><a href="best-practices-evaluation#bbva">1/8</a></td>
		</tr>
		<tr class="bank-row" id="la-caixa">
			<td><a href="banks/es/la-caixa">La Caixa</a></td>
			<td>ES </td>
			<td><i class="fas fa-globe-americas"></i> </td>
			<td><i class="fas fa-table"></i> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
			<td><bold>E</bold>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, <img src="res/img/binding/mfa_icon.png" height="12pt" />  </td>
			<td>IP-11<br/> IP-26 </td>
			<td>MP-19</td>
			<td><i class="fas fa-check-double"></i></td>
			<td><a href="requirements-evaluation#la-caixa">6/9</a></td>
			<td><a href="best-practices-evaluation#la-caixa">4/8</a></td>
		</tr>
		<tr class="bank-row" id="ing">
			<td><a href="banks/nl/ing">ING</a></td>
			<td>NL	</td>
			<td><i class="fas fa-globe-americas"></i> </td>
			<td><i class="fas fa-table"></i> <br/> <span class="authr-data-obj">otp</span><img class="authr-img channel" src="res/img/channels/chanin_m.png"  /> <i class="fas fa-sim-card"></i><sup class="authr-info">?</sup> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /><i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[I]</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
			<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, -- <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>(<i class="fas fa-sim-card"></i>) </td>
			<td> IP-11 <br/> IP-15 <br/> IP-27  </td>
			<td>MP-19 <br/> MP-27 </td>
			<td><i class="fas fa-check"></i></td>
			<td><a href="requirements-evaluation#ing">2/9</a></td>
			<td><a href="best-practices-evaluation#ing">3/8</a></td>
		</tr>
		<tr class="bank-row" id="rabobank">
			<td><a href="banks/nl/rabobank">Rabobank</a></td>
			<td>NL	</td>
			<td><i class="fas fa-globe-americas"></i> </td>
			<td><span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_o.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[I]</span>  </td>
			<td><bold>E</bold>,<i class="fas fa-university"></i>,<i class="fas fa-university"></i> <br/> -- <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, --  </td>
			<td>IP-7 <br/> IP-10 </td>
			<td>MP-9 <br/> MP-24 </td>
			<td> <i class="fas fa-check-double"></i> </td>
			<td><a href="requirements-evaluation#rabobank">7/9</a></td>
			<td><a href="best-practices-evaluation#rabobank">3/8</a></td>
		</tr>
		<tr class="bank-row" id="abn-amro">
			<td><a href="banks/nl/abn-amro">ABN AMRO</a></td>
			<td>NL	</td>
			<td><i class="fas fa-globe-americas"></i> </td>
			<td><span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><span class="authr-afs">[I]</span>  </td>
			<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> -- <br/> <i class="fas fa-globe-americas"></i>, <i class="fas fa-globe-americas"></i>, --<br/>  </td>
			<td>IP-5 <br/> IP-10 </td>
			<td> MP-5 <br/> MP-5, <br/> MP-23 <br/> MP-23  </td>
			<td><i class="fas fa-check-double"></i></td>
			<td><a href="requirements-evaluation#abn-amro">6/9</a></td>
			<td><a href="best-practices-evaluation#abn-amro">2/8</a></td>
		</tr>
		<tr class="bank-row" id="nordea">
			<td><a href="banks/sw/nordea">Nordea</a></td>
			<td>SW	</td>
			<td><i class="fas fa-globe-americas"></i> </td>
			<td><span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <i class="fas fa-calculator"></i><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
			<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
			<td> IP-5 <br/> IP-8 <br/> IP-13 <br/> IP-27 <br/> IP-28  </td>
			<td> MP-3 <br/> MP-20 <br/>MP-21  </td>
			<td><i class="fas fa-check-double"></i></td>
			<td><a href="requirements-evaluation#nordea">4/9</a></td>
			<td><a href="best-practices-evaluation#nordea">4/8</a></td>
		</tr>
		<tr class="bank-row" id="svenska-handelsbanken">
			<td><a href="banks/sw/svenska-handelsbanken">Svenska<br/>Handelsbanken</a></td>
			<td>SW	</td>
			<td><i class="fas fa-university"></i> </td>
			<td><i class="fas fa-table"></i> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <i class="fas fa-calculator"></i><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span>  </td>
			<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" />  </td>
			<td> IP-5 <br/> IP-8 <br/> IP-11 <br/> IP-13<br/>IP-27 <br/> IP-28 </td>
			<td> MP-3 <br/> MP-10 <br/> MP-20 <br/> MP-21 </td>
			<td><i class="fas fa-times"></i></td>
			<td><a href="requirements-evaluation#svenska-handelsbanken">4/9</a></td>
			<td><a href="best-practices-evaluation#svenska-handelsbanken">4/8</a></td>
		</tr>
		<tr class="bank-row" id="seb">
			<td><a href="banks/sw/seb">SEB</a></td>
			<td>SW	</td>
			<td><i class="fas fa-globe-americas"></i> </td>
			<td><span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_h.png"  /> <i class="fas fa-calculator"></i><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_h.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <i class="fas fa-calculator"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_n.png"  /> <i class="fas fa-mobile-alt"></i><sup class="authr-info">?</sup><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_n.png"  /><span class="authr-data-obj">otp</span> <br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,K]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span><br/> <span class="authr-data-obj">opid</span><img class="authr-img channel" src="res/img/channels/chanin_i.png"  /> <img class="authr-img obj" src="res/img/authenticators/sw.png"  /><sup class="authr-info">?</sup><span class="authr-afs">[O,I]</span> <img class="authr-img channel" src="res/img/channels/chanout_i.png"  /><span class="authr-data-obj">otp</span> </td>
			<td><bold>E</bold>,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <img src="res/img/binding/mfa_icon.png" height="12pt" />,<i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> <br/> <i class="fas fa-globe-americas"></i>,<i class="fas fa-globe-americas"></i>,<img src="res/img/binding/mfa_icon.png" height="12pt" /> </td>
			<td> IP-5 <br/> IP-8<br/> IP-27 <br/> IP-28 </td>
			<td> MP-3 <br/> MP-20 <br/> MP-21 </td>
			<td> <i class="fas fa-times"></i></td>
			<td><a href="requirements-evaluation#seb">4/9</a></td>
			<td><a href="best-practices-evaluation#seb">3/8</a></td>
		</tr>
	</table>
</div>

<h2>Non-EU Banks</h2>

<div id="eu-table-wrapper" style="overflow-x: scroll;">
	<table id="non-eu-banks-table" style="color: black;">
		<thead style="font-weight: bold; font-size: 12.5pt;">
			<td>Bank name</td>
			<td>C</td>
			<td>Enr.</td>
			<td>Authenticators</td>
			<td>Binding</td>
			<td>IPs</td>
			<td>MPs</td>
			<td>Ex.</td>
			<td>RLs</td>
			<td>BPs</td>
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
			<td><a href="requirements-evaluation#icbc">6/9</a></td>
			<td><a href="best-practices-evaluation#icbc">4/8</a></td>
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
			<td><a href="requirements-evaluation#ccb">6/9</a></td>
			<td><a href="best-practices-evaluation#ccb">4/8</a></td>
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
			<td><a href="requirements-evaluation#abc">6/9</a></td>
			<td><a href="best-practices-evaluation#abc">5/8</a></td>
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
			<td><a href="requirements-evaluation#chase">2/9</a></td>
			<td><a href="best-practices-evaluation#chase">2/8</a></td>
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
			<td><a href="requirements-evaluation#bank-of-america">2/9</a></td>
			<td><a href="best-practices-evaluation#bank-of-america">1/8</a></td>
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
			<td><a href="requirements-evaluation#wells-fargo">2/9</a></td>
			<td><a href="best-practices-evaluation#wells-fargo">2/8</a></td>
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
			<td><a href="requirements-evaluation#ubs">6/9</a></td>
			<td><a href="best-practices-evaluation#ubs">4/8</a></td>
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
			<td><a href="requirements-evaluation#credit-suisse">4/9</a></td>
			<td><a href="best-practices-evaluation#credit-suisse">2/8</a></td>
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
			<td><a href="requirements-evaluation#raiffeisen">4/9</a></td>
			<td><a href="best-practices-evaluation#raiffeisen">1/8</a></td>
		</tr>
	</table>
</div>

<script>
	var $table = $("#eu-banks-table");
	$table.floatThead();
	$("#non-eu-banks-tableeu-banks-table").floatThead();
</script>