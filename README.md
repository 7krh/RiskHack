# RiskCheat

RiskCheat repository for research / educational tooling around the game **Risk: Global Domination**.  
> ⚠️ **Important — For ethical use only.**  
> Use RiskHack only in controlled environments (your own accounts, private servers, or with explicit permission). Do **not** use this project to cheat in online games, circumvent anti-cheat mechanisms, infringe terms of service, or harm other users. The authors are not responsible for misuse.


---

## Features
	
	Works with /GS- compiled drivers
	Hooks NtAddAtom which exists everywhere and is rarely called
	Clears MmUnloadedDrivers
	Clears PiDDBCacheTable
	Clears g_KernelHashBucketList
	Clears Wdfilter RuntimeDriverList RuntimeDriverCount and RuntimeDriverArry
	Use NtLoadDriver and NtUnloadDriver for less traces
	Prevent load if \Device\Nal exists (Prevents BSOD)
	Header section skipped while copying driver to kernel
	Added the possibility to modify params before call driver entry
	Added PDB_OFFSETS macro that will allow the use of Offset PDB features (choose the target build)
	Introduced new project "SymbolsFromPDB" that will help KDMapper to adapt quickly to any windows updates by parsing the target .PDB files (PDB_OFFSETS macro must be defined to use this feature)

---

## Quick notes

- **This repository does NOT include or promote tools to bypass anti-cheat or gain unfair advantage in online matches.**  
- **Always test on private/local copies of the game or explicitly permitted test environments.**
- Keep sensitive data (API keys, account credentials, live server IPs) out of the repo.

---

## Parameters (starter CLI)

These are example command-line flags to be implemented as the codebase grows. They are **placeholders** — implement only ethical features.

