*uxsearch - Object search*
=============


uxsearch.ksh is a tool designed to search for objects.
http://github.com/Automic-Community/uxsearch---Object-search

<!-- List of attached files -->
Contents of Solution Package:

						
								*uxsearch.zip
								
						


Documenation and Instructions
---

<p><strong class="title">Description</strong></p>
<p>uxsearch.ksh is a tool designed to search for objects (such as Applications, Classes, conditions, Resources, Rules, Uproc variables...) used in Dollar Universe Uprocs / Sessions / Tasks.</p>
<p>&nbsp;</p>
<p><strong class="title">Target environments:</strong> Unix, Linux</p>
<p><strong class="title">Prerequisites:</strong></p>
<ul style="list-style-type: circle;">
<li>Dollar Universe 5.x</li>
<li>Dollar Universe 6.0.x</li>
</ul>
<p><strong class="title">Implementation:</strong> Copy the file uxsearch on your server.</p>
<p>&nbsp;</p>
<p><br /> Usage:<br /> #<br /> # uxsearch.ksh [--env_options] Theme=Value [Theme=Value] [...]<br /> #<br /> # where --env_options are:<br /> # --soc COMPANY. By default: --soc=$S_COMPANY<br /> # --node NODE. By default: --node=$S_NOEUD<br /> # --space [EXP|SIM|INT|APP] or [X|S|I|A]. By default: --space=$S_ESPEXE<br /> #<br /> # where Theme=Value format is:<br /> # appl=ApplicationName where appl=[a-Z|A-Z|0-9|_|\*]*<br /> # class=ClassName where class=[a-Z|A-Z|0-9|_|\*]*<br /> # clfil=ScriptName where clfil=[a-Z|A-Z|0-9|_|\*]<br /> # definfo=DefaultInformation where definfo=[a-Z|A-Z|0-9|_|\*| ]"<br /> # defsev=DefaultSeverity where defsev=[a-Z|A-Z|0-9|_|\*| ]"<br /> # depcon=UprocName where depcon=[a-Z|A-Z|0-9|_|\*]<br /> # incclass=IncompatibilityClassName where Incclass=[a-Z|A-Z|0-9|_|\*]*<br /> # res=RessourceName where res=[a-Z|A-Z|0-9|_|\*]*<br /> # rul=RuleName where rul=[a-Z|A-Z|0-9|_|\*]*<br /> # upr=UprocName where upr=[a-Z|A-Z|0-9|_|\*|\.]*<br /> # varname=VariableName where var=[a-Z|A-Z|0-9|_|\*]*<br /> # vvalue=VariableValueName where vvalue=[a-Z|A-Z|0-9|_|\*]*<br /> #<br /> # uxsearch.ksh [help|-h|--help]<br /> <br /> You can provide the environment to work upon (Company, Node, Area).</p>

Copyright and License
---

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)


Questions or Need Help? 
---
Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
