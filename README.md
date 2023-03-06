# Formal Verification And Consensus-Based Defense System for Cyber-Physical Networks

This project is a demonstration of a byzantine fault-tolerant consensus mechanism overlay and formal verification guard checks to ensure the security of a cyber-physical network (CPN) between mutually distrusting parties. In this particular case, the CPN is a network of individual natural gas pipeline networks owned by different suppliers that may/may not display byzantine behavior. 

This system prevents the reachability of unsafe states (ie: Gas Siphoning Attack, Natural Gas Plant Explosion, etc.) by any natural gas plant in the byzantine system. The repo contains the simulations, modeled in Matlab, Simulink, and Stateflow, for both initially insecure and revised secure SLSX Models of open-source Russia-EU-Ukrain natural gas pipeline, with supporting literature attached below. A naive voting based consensus layer is added atop to compare the state results of each cyber-physical subnet and detect any disparities in real time.

The full explanation and process is within the attached papers- most notably; "Detecting Security Leaks In Hybrid Systems with Information Flow Analysis" by Nguyen et al. 
