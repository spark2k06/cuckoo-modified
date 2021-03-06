This is a heavily modified version of Cuckoo Sandbox provided under the GPL by Accuvant, Inc.

It offers a number of advantages over the upstream Cuckoo:
+ Fully-normalized file and registry names
+ 64-bit analysis
+ Handling of WoW64 filesystem redirection
+ Many additional API hooks
+ Service monitoring
+ Correlates API calls to malware call chains
+ Ability to follow APC injection and stealth explorer injection
+ Pretty-printed API flags
+ Per-analysis Tor support
+ ~40 new signature modules
+ Anti-anti-sandbox and anti-anti-VM techniques built-in
+ More stable hooking
+ Ability to restore removed hooks
+ Greatly improved behavioral analysis and signature module API
+ Hundreds of other bugfixes

For more information on the initial set of changes, see:
http://www.accuvant.com/blog/improving-reliability-of-sandbox-results
An updated blog post covering more recent changes is forthcoming.

If you want to contribute to development, submit pull requests or email bspengler@accuvant.com.