This is the client mod for HeroMod
===
Make this not crap :D

https://github.com/unknownloner/HeroModServ

3:30 AM <unknownloner> anyways Kainzo use this https://github.com/unknownloner/HeroModServ to get rid of the dependance of heromod on my server
3:30 AM <unknownloner> I'm sure you're smart enough to figure out how to change the domain in the HeroMod source
3:30 AM <unknownloner> you need nodejs
3:30 AM <unknownloner> git clone the repo
3:30 AM <unknownloner> cd into the directory
3:31 AM <unknownloner> run 'npm install'
3:31 AM <unknownloner> and then to launch the server run 'node heromod_serv.js'
3:31 AM <unknownloner> in a screen of course, or however you wanna do it
3:31 AM <unknownloner> then you're good to go

To Compile.
12:37 PM <unknownloner> Ant + MCP + LiteLoader
12:39 PM <unknownloner> The README has links to MCP, and the guide for setting up LiteLoader with MCP
12:40 PM <unknownloner> there is an ant file in the ant/ folder of the HeroMod repository called 'build.xml' which will build the mod if you've set up LiteLoader and the mod's source properly, and have run LiteLoader's build script before hand
12:40 PM <unknownloner> I usually run it from inside of eclipse although you can run the command directly from command line if it suits you
12:41 PM <unknownloner> Sorry for the late reply, I was sleeping
12:42 PM <unknownloner> anyways the ant script handles everything from compiling to reobfuscating to creating the final .litemod file
