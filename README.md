# Perf_Tuning
Different methods for software performance tuning

The research project is about finding a way to identify the configuration options that may be performance-influential. For example, in a simulator called PPSSPP, there are many configuration options to tune the performance. The default settings may not always be good, and PPSSPP could run very slow. And because PPSSPP has a lot of configuration options, it may not be very easy to figure out which ones to change to get better performance.

# Approaches
1. NLP, use the name tokens in the configuration file to rank a list of configuration options 
2. NLP + Data Mining, use data mining on online documentation, discussion board (stackoverflow) etc to output a ranked list of configuration options
3. Associate the configuration option with the source code, to find a way to evaluate their perofrmance
