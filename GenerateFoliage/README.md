![1](https://github.com/pto8913/UE4_memo/blob/images/generate/gen_foli.gif)<br>

If you use this, change your project name "MYPROJECT2" in BPFL_GenerateFoliage.h <br>
And, you should add `PrivateDependencyModuleNames.AddRange(new string[] { "Foliage" });` <br>

note: Need to exists foliage object in your world. if not exists foliage, your project is crushed. <- BPFL_GenerateFoliage <br>

fix: Generate foliage from your game assets at begin game. <- GenerateFoliageActor.cpp and .h
