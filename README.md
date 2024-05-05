15-494 S24 final project, by Peter Khoudary and Shruti Srinivasan.

HOW TO RUN:
Given you have a cozmo setup and ready, make sure you have an openai key in your environment. Once this is done, genfsm DemoFinal.fsm, and run it in simple_cli.
You can interact with cozmo using tm messages, and can ask cozmo whatever. If you ever asked cozmo for a path / he describes a path he could take, you can use "tm run path" to have him drive the most recent path he suggested. You may
also find it fruitful to manually drive him around and see how he updates the gridview.

NOTE: The run path functionality was not implemented at time of shooting demo video, but is now. So if you're running an experiment similar to one we did in the demo video, you can just call run path instead.
