# HybridThermoFoam
# Compile with optimization
g++ -O3 -std=c++11 -o hybridthermofoam hybridthermofoam.cpp

# Run simulation
./hybridthermofoam

# Visualize results
python visualize_results.py hybridthermofoam_results.csv
