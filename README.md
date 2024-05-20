**Task Description**
This assignment involved reading a list of integers from an input file using Python and generating an output file containing a list of unique integers present in the 
input file. The output integers are sorted in increasing order.

**Code Description**
UniqueInt.py: This file contains the main code for processing the input files and generating the output files with unique, sorted integers.


**Functions**
1. processFile(source_file, destination_file)
   Reads the input file, extracts unique integers, sorts them, and writes them to the output file.
2. extract_and_sort_unique_integers(source_file_path)
   Extracts unique integers from the input file and returns them as a sorted list.
3. insert_in_sorted_order(sorted_list, value)
   Inserts a value into the sorted list while maintaining the sorted order and avoiding duplicates.
4. save_integers_to_file(destination_file_path, integers)
   Writes each integer from the list to the specified output file, one per line.
5. handle_file_operations(source_file_path, destination_file_path)
Manages the overall process of reading from the source file, processing the integers, and saving them to the destination file.
