# Compile
g++ -std=c++17 -o asm_analyser_agg asm_analyser_aggressive.cpp

# Run with different modes:
./analyser program.disas                      # Conservative (factor 2/1)
./analyser program.disas --aggressive         # 2× multipliers (factor 4/2)
./analyser program.disas --very-aggressive    # 4× multipliers (factor 8/4)
./analyser program.disas --max-factor 4       # Custom max (factor 4)
./analyser program.disas --no-cache-limit     # Ignore I-cache limits

