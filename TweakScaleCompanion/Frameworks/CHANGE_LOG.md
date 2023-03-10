# TweakScale Companion :: Frameworks :: Change Log

* 2021-0926: 0.2.0.0 **Beta** (LisiasT) for KSP >= 1.8
	+ Refactoring:
		- Using recent KSPe.Light.TweakScale features to allow selective loading of DLLs bound to 3rd-parties, allowing the Companion to be used on installments where these dependencies are not preset.
		- A lot of flexibility on deployment are available now.  
* 2021-0919: 0.1.0.2 **Beta** (LisiasT) for KSP >= 1.8
	+ A less than ideal initialisation routine were fixed.
	+ Closes Issues:
		- [#2](https://github.com/net-lisias-ksp/TweakScaleCompanion_Visuals/issues/2) Race Condition while initialising the PartModule
* 2021-0908: 0.1.0.1 **Beta** (LisiasT) for KSP >= 1.8
	+ Short circuiting some Dependency Checks due a new misbehaviour introduced on KSP 1.12.2
* 2021-0705: 0.1.0.0 **Beta** (LisiasT) for KSP >= 1.8
	+ (Properly) declares dependencies now
	+ Slightly faster patching when dependencies are not met. 
	+ Promotes the thingy to Beta status
		- See [KNOWN ISSUES](./KNOWN_ISSUES.md). 
* 2021-0626: 0.0.2.0 **ALPHA** (LisiasT) for KSP >= 1.8
	+ Rework initialisation procedures to cope with the new KSP 1.12 idiosyncrasies
	+ DLL is compiled in Release mode from now on.
* 2021-0530: 0.0.1.0 **ALPHA** (LisiasT) for KSP >= 1.8
	+ Initial public release
	+ **ALPHA** release, not ready for "production"
		- Compiled in DEBUG mode
		- See [KNOWN ISSUES](./KNOWN_ISSUES.md). 
