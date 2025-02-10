<main _ngcontent-rjj-c89="" class="content-area"><router-outlet _ngcontent-rjj-c89=""></router-outlet><app-explorer _nghost-rjj-c95="" class="ng-star-inserted"><div _ngcontent-rjj-c95="" class="explorer-content-area"><div _ngcontent-rjj-c95="" class="doc-container ng-star-inserted"><div _ngcontent-rjj-c95="" class="content-area doc-area"><router-outlet _ngcontent-rjj-c95=""></router-outlet><app-topic-doc _nghost-rjj-c97="" class="ng-star-inserted"><div _ngcontent-rjj-c97="" class="ng-star-inserted"><div _ngcontent-rjj-c97="" class="clr-row"><div _ngcontent-rjj-c97="" class="clr-col-xs-12"><h1 _ngcontent-rjj-c97="">Topic Documentation</h1><h2 _ngcontent-rjj-c97="" class="doc-subheading">Patient Based Scheduling</h2></div></div><div _ngcontent-rjj-c97="" class="clr-row ng-star-inserted"><div _ngcontent-rjj-c97="" class="clr-col-xs-12"><h3 _ngcontent-rjj-c97="">Description</h3><markdown _ngcontent-rjj-c97=""><p>MEDITECH's Argo-Scheduling APIs are based on the <a href="https://argonautproject.github.io/scheduling/patient-scheduling.html">Argo-Scheduling Implementation Guide CI Build</a>
which conform to the <a href="http://hl7.org/fhir/STU3/index.html">FHIR STU 3, v3.0.1</a>. <br><br></p>
<blockquote>
<p><strong>API Endpoints</strong> Please contact the health care organization for more information about their API endpoints.  Depending on the size and complexity of the health care organization's facility footprint, there may be multiple API endpoints associated with a single organization.</p>
</blockquote>
<h3 id="terms-of-use-">Terms of Use <br><br></h3>
<p>In order to use these APIs, developers must agree to the <a href="https://home.meditech.com/en/d/restapiresources/pages/apiterms.htm">Terms of Use</a>.</p>
<h3 id="application-configuration-">Application Configuration <br><br></h3>
<p>Developers wishing to leverage the Argo-Scheduling APIs in an application must contact the hospital's System Administrator in order to configure the hospital's system to work with the application. <br><br></p>
<p>This configuration involves setting up the appropriate <a href="https://oauth.net/2/">OAuth 2.0</a> parameters such as: <br><br></p>
<ul>
<li>Client Id</li>
<li>Client Secret</li>
<li>Redirect URI <br></li>
</ul>
<blockquote>
<p><strong>Application Security</strong> Application configuration allows the MEDITECH HCIS to identify which applications are accessing the Argo-Scheduling APIs.  It also allows the MEDITECH HCIS to limit access should an application become compromised or malfunction.</p>
</blockquote>
<h3 id="authentication-">Authentication <br><br></h3>
<p>Applications have different types of users and different authentication schemes; each requiring a different security model. <br><br></p>
<p><strong>Patients</strong> <br><br></p>
<p>Applications developed for Patient usage require that the patient authenticates with an Identity Provider before an access
token can be granted to the application. <br><br></p>
<p>MEDITECH supports the <a href="http://openid.net/connect/">OpenID Connect</a> protocol and has tested with the following Identity Providers: <br><br></p>
<ul>
<li><a href="https://developers.google.com/identity/protocols/OpenIDConnect">Google Identity</a> <br></li>
</ul>
<blockquote>
<p><strong>Identity Providers</strong> Application developers may need to register their applications with the Identity Provider in order to leverage their services.</p>
</blockquote>
<blockquote>
<p><strong>OpenID Connect</strong> MEDITECH supports <a href="http://openid.net/connect/">OpenID Connect</a> but may require additional configuration to work with
Identity Providers outside of those noted above.</p>
</blockquote>
<blockquote>
<p><strong>Credentials</strong> Authentication occurs with third party Identity Providers. MEDITECH does not capture or maintain user credentials.</p>
</blockquote>
<h3 id="patient-linking-">Patient Linking <br><br></h3>
<p>The linking of an Identity to a patient record in the MEDITECH HCIS is a manual process that must be completed by staff
member of the medical institution. <br><br></p>
<p>Once the Identity to Patient link is established, the access to patient records will be limited to those that are
associated to the Identity. <br></p>
<blockquote>
<p><strong>Health Care Proxies</strong> It is possible to establish a Health Care Proxy by associating the Identity of the proxy to a patient record.</p>
</blockquote>
</markdown><!----></div></div><!----><div _ngcontent-rjj-c97="" class="clr-row"><div _ngcontent-rjj-c97="" class="clr-col-xs-6 ng-star-inserted"><table _ngcontent-rjj-c97="" class="table table-compact"><thead _ngcontent-rjj-c97=""><tr _ngcontent-rjj-c97=""><th _ngcontent-rjj-c97="" class="left">API</th></tr></thead><tbody _ngcontent-rjj-c97=""><tr _ngcontent-rjj-c97="" class="ng-star-inserted"><td _ngcontent-rjj-c97="" class="left"><a _ngcontent-rjj-c97="" href="/explorer/api/argoScheduling._.%252Ewell-known._/2">v2/argoScheduling/{implementationVersion}/.well-known/{id}/</a></td></tr><tr _ngcontent-rjj-c97="" class="ng-star-inserted"><td _ngcontent-rjj-c97="" class="left"><a _ngcontent-rjj-c97="" href="/explorer/api/argoScheduling._.Appointment/2">v2/argoScheduling/{implementationVersion}/Appointment/</a></td></tr><tr _ngcontent-rjj-c97="" class="ng-star-inserted"><td _ngcontent-rjj-c97="" class="left"><a _ngcontent-rjj-c97="" href="/explorer/api/argoScheduling._.Appointment._/2">v2/argoScheduling/{implementationVersion}/Appointment/{id}/</a></td></tr><tr _ngcontent-rjj-c97="" class="ng-star-inserted"><td _ngcontent-rjj-c97="" class="left"><a _ngcontent-rjj-c97="" href="/explorer/api/argoScheduling._.Appointment._._/2">v2/argoScheduling/{implementationVersion}/Appointment/{id}/{operation}/</a></td></tr><tr _ngcontent-rjj-c97="" class="ng-star-inserted"><td _ngcontent-rjj-c97="" class="left"><a _ngcontent-rjj-c97="" href="/explorer/api/argoScheduling._.Location/2">v2/argoScheduling/{implementationVersion}/Location/</a></td></tr><tr _ngcontent-rjj-c97="" class="ng-star-inserted"><td _ngcontent-rjj-c97="" class="left"><a _ngcontent-rjj-c97="" href="/explorer/api/argoScheduling._.Location._/2">v2/argoScheduling/{implementationVersion}/Location/{id}/</a></td></tr><tr _ngcontent-rjj-c97="" class="ng-star-inserted"><td _ngcontent-rjj-c97="" class="left"><a _ngcontent-rjj-c97="" href="/explorer/api/argoScheduling._.Patient/2">v2/argoScheduling/{implementationVersion}/Patient/</a></td></tr><tr _ngcontent-rjj-c97="" class="ng-star-inserted"><td _ngcontent-rjj-c97="" class="left"><a _ngcontent-rjj-c97="" href="/explorer/api/argoScheduling._.Patient._/2">v2/argoScheduling/{implementationVersion}/Patient/{id}/</a></td></tr><tr _ngcontent-rjj-c97="" class="ng-star-inserted"><td _ngcontent-rjj-c97="" class="left"><a _ngcontent-rjj-c97="" href="/explorer/api/argoScheduling._.Practitioner/2">v2/argoScheduling/{implementationVersion}/Practitioner/</a></td></tr><tr _ngcontent-rjj-c97="" class="ng-star-inserted"><td _ngcontent-rjj-c97="" class="left"><a _ngcontent-rjj-c97="" href="/explorer/api/argoScheduling._.Practitioner._/2">v2/argoScheduling/{implementationVersion}/Practitioner/{id}/</a></td></tr><!----></tbody></table></div><!----><!----><!----><!----><!----><!----></div><!----></div><!----></app-topic-doc><!----></div></div><!----><!----><!----><!----></div></app-explorer><!----></main>
