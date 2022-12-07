# CP4CIP

# Command line :
# Datasets  were transformed to fit solver requirement on having only intergers as a domain in Or-tools API, see the paper in experimental protocol.
# This transformation are saved in python3 dictionnary objects "*idval.dic and "*valid.dic" to reconstruct the original values from the output of our results.

# Two binary code are available, on can be running on ubuntu 18 and the other on ubuntu 20.
# before executing the commands, OR-tools library should be included as environment variable by the following command :
export LD_LIBRARY_PATH="YourDirectoryContainingFiles/bin/:$LD_LIBRARY_PATH"
export LIBRARY_PATH="YourDirectoryContainingFiles/bin/:$LD_LIBRARY_PATH"


# launching CP4CIP using only binary dataset 
/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/cp4cip-cpsolver/example/example-0v8-43200.time' timeout 43200 'bin/CP4CIP-Ubuntu-20.04.bin' --cp4cip-cpsolver  'data/example/example_T.dat' 0.8 0 ; echo "Exit status: $?" 
/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/cp4cip-cpsolver/example/example-0v2-43200.time' timeout 43200 'bin/CP4CIP-Ubuntu-20.04.bin' --cp4cip-cpsolver  'data/example/example_T.dat' 0.2 0 ; echo "Exit status: $?" 
/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/cp4cip-cpsolver/example/example-0v5-43200.time' timeout 43200 'bin/CP4CIP-Ubuntu-20.04.bin' --cp4cip-cpsolver  'data/example/example_T.dat' 0.5 0 ; echo "Exit status: $?" 

# launching cp4im interordinal scaling is carried out internally

/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/cp4im-cpsolver/example/example-0v8-43200.time' timeout 43200 'bin/CP4CIP-Ubuntu-20.04.bin' --cp4im-cpsolver  'data/example/example.dat' 0.8 0 ; echo "Exit status: $?" 
/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/cp4im-cpsolver/example/example-0v5-43200.time' timeout 43200 'bin/CP4CIP-Ubuntu-20.04.bin' --cp4im-cpsolver  'data/example/example.dat' 0.5 0 ; echo "Exit status: $?" 
/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/cp4im-cpsolver/example/example-0v2-43200.time' timeout 43200 'bin/CP4CIP-Ubuntu-20.04.bin' --cp4im-cpsolver  'data/example/example.dat' 0.2 0 ; echo "Exit status: $?" 

# launching minintchange

/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/minintchange/example/example-0v8-43200.time' timeout 43200 java -jar 'bin/MinIntChange.jar'  'data/example/example.dat' 4 ; echo "Exit status: $?" 
/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/minintchange/example/example-0v5-43200.time' timeout 43200 java -jar 'bin/MinIntChange.jar'  'data/example/example.dat' 3 ; echo "Exit status: $?" 
/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/minintchange/example/example-0v2-43200.time' timeout 43200 java -jar 'bin/MinIntChange.jar'  'data/example/example.dat' 1 ; echo "Exit status: $?" 


# launching CP4CIP using only binary dataset 
/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/example/example-0v5-43200.time' timeout 43200 'bin/CP4CIP-Ubuntu-20.04.bin' --cp4cip-cpsolver  'data/example/example_IS_BIN.dat' 0.5 0 ; echo "Exit status: $?" 
/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/example/example-0v2-43200.time' timeout 43200 'bin/CP4CIP-Ubuntu-20.04.bin' --cp4cip-cpsolver  'data/example/example_IS_BIN.dat' 0.2 0 ; echo "Exit status: $?" 
/usr/bin/time -f "%E real , %U user , %S sys" -o 'results/example/example-0v8-43200.time' timeout 43200 'bin/CP4CIP-Ubuntu-20.04.bin' --cp4cip-cpsolver  'data/example/example_IS_BIN.dat' 0.8 0 ; echo "Exit status: $?" 

