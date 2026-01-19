# AICB
For a short RL project in class, I tried to teach a reinforcement learning agent to control an economy as would be done by a real-life central banker. Building on past papers, I tried to introduce more realism by including a novel forward guidance mechanism into the system. It works by setting some Bayesian priors on statements, helping encode some helpful biases that give forward guidance statements their meanings. 

This is, of course, a very short project with many simplifications. The mechanism I developed for forward guidance, for example, isn't really all that realistic and a lot more work has to go into it. It only has implications for the next time step $t + 1$, while usually forward guidance by Central Bankers aims to influence long-term rates, while here no such thing was modeled. The way that I combined current interest rates with expected interest rates is also a bit sloppy.

Still, this was quite a lot of fun and I really enjoyed reading some classic papers from the monetary policy literature and combining it with modern-day RL. I think I'll give this another shot when I have more time. If you are interested, you can also read the report I wrote for class, which is included in the repository.

PS: The coding up of the environment and training the model was done by me, but I relied heavily on Claude and ChatGPT for the visualisation portion.
