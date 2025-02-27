INSTRUCTION MANUAL FOR OPERATION
  Greetings to you, Ale-enthusiast! 
  You have stumbled across The Wolf's Stupor, my simulated brewery process as part of the IBM i-UG Node-RED Education Programme.
  This flow is based off of an original template for 'The Brewery', which featured manual input sliders to simulate a process relying on constant human supervision. However, the objective as stated in the brief
  was to automate this flow, so as to minimise the level of supervision required and optimise production to be as efficient as possible.
  I completely reengineered the entire process, rewriting and recoding from the ground-up, to employ more intuitive variable names and easier to track processes. I also incorporated new features with principles of
  Lean Manufacturing in mind, such as a case stock and replenishment post-delivery, heat cut-off if temperature within a stable range, a daily production limit in consideration of overproduction, and basic cost 
  and revenue tracking by dynamic calculation.
  For my first coding project, this was a great challenge that established my skills in JavaScript, process management, IoT integration, real-time data analytics, troubleshooting, and discovering my talent for 
  employing a developer mindset. I hope you enjoy.

  To operate the flow:
    -  Open the flow, and additionally open the flow's UI (i.e. normally, you only have to copy and paste the flow URL into a new tab and append /ui to precede /#flow/12345 - e.g. /ui/#flow/12345).
    -  Set the case production per second (1 is preferable to start with to get familiar with the process).
    -  Under 'PRODUCTION CONTROL' (top-left box on the flow diagram), locate the 'toggle gates' and 'initialise brewing' injectors.
    -  Toggle the gates first: you'll notice several gates across the flow change their status from 'closed' to 'open'. By doing this, communication across the flow is disinhibited.
    -  Initialise brewing: check the logs to ensure operation
    -  Observe production via the UI. Configure case production as desired (NOTE: tested successfully up to 12 cases/sec).
