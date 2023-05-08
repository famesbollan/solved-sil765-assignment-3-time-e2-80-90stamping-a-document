Download Link: https://assignmentchef.com/product/solved-sil765-assignment-3-time%e2%80%90stamping-a-document
<br>
This application relates to time‐stamping a document that one may have prepared some moments ago. The process envisaged is: upload the document to server (or some version thereof) and expect to receive the same but with the current date and time stamped onto the document. Thus there must exist a “GMT date &amp; time‐stamping server” which has the correct GMT date and time. It uses that to time‐stamp document (in some standard format) with the current GMT data/time and a digital signature. At any time, it should be possible to establish the fact that the document existed at the date/time stamped, and that the document <u>has not been modified</u>.

Further:

<ol>

 <li>How and where do you get the correct GMT date and time? And how often?</li>

 <li>Is the source reliable and the GMT date and time obtained in a secure manner?</li>

 <li>How do you ensure privacy, in that the server does not see/keep the original document?</li>

 <li>How do you share the document with others in a secure manner with the date/time preserved, and integrity un‐disturbed?</li>

 <li>Also ensure that the user has (and uses) the correct “public‐key” of the “GMT date/time stamping server”.</li>

</ol>

<strong><u>Project 1</u></strong>: This application relates to building a web server that responds with a degree‐certificate and grade‐card whenever someone requests for it. The request must contain the graduate’s unique entrynumber. The degree‐certificate (possibly in PDF format) is suitably digitally signed by the university authorities, together with the current (and correct) time.

<ol>

 <li>How and where do you get the correct GMT date and time? Is the source reliable and the GMT date and time obtained in a secure manner?</li>

 <li>How do you get the document to be signed by more than one individual (say two persons)?</li>

 <li>How do you ensure that only the graduate is able to download it (by providing information beyond the entry_no, such as date of birth, home pin code, etc.?</li>

 <li>Should the graduate decide to share the document with others, how can one trace the origin of the document (could watermarks be useful?)?</li>

 <li>Do we need to have access to public‐keys, and if so how?</li>

</ol>

<strong><u>Project 2:</u></strong> The origin of this lies in UID project of GoI, where a central server can be accessed to determine whether some information on an individual is correct or not, but without divulging the information itself. For instance, the database will help determine whether BNJ’s DoB is xxx or not, but without the database server itself volunteering such information. How can we do this in a secure and trusted manner.

<ol>

 <li>One question that arises is: how does one ensure that information is not altered during the 2way communication between the client and server?</li>

 <li>How could one be sure that the reply from UID server “Yes” or “No” is related to the question being asked?</li>

 <li>In what way are digital signatures relevant?</li>

 <li>Would access to “public‐key certificate” issued by a certification authority be an issue?</li>

</ol>

<strong><u>Project 3:</u></strong> This project has to do with verifying a document such as a “driver’s license”. (Truly this holds good for any “identity card” or any official document such as a passport or birth certificate.) Typically, and currently, a police officer looks at the physical driver’s license card and simply assumes that the license, together with the information it contains, was issued by the “transport authority”. Given that it is not so difficult to copy, alter or produce afresh a plastic card, how can one use technology to verify <u>on</u> <u>the go</u> the veracity of a driver license card, when shown to a police officer on the road or elsewhere. (Recall: today cellular based access to Internet‐connected servers from smart cell phones is readily available, almost all parts of India.) Questions:

<ol>

 <li>What is the information to be supplied by the driver to the police officer? And what information is sought and obtained from the transport authority?</li>

 <li>Would you need a central server that has the correct and complete information on all drivers and the licenses issued to them?</li>

 <li>Is date and time of communication important?</li>

 <li>In what way are digital signatures relevant?</li>

 <li>How does one ensure that information is not altered during the 2‐way communication?</li>

 <li>Which of these, viz. confidentiality, authentication, integrity and non‐repudiation relevant?</li>

</ol>


