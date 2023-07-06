#Employee Management

The Employee Management project is a Python script that performs various operations on a list of employee dictionaries. It includes functions to modify the employee list, generate usernames, and map employee IDs to their first initials.


# Functions

to_mod_list(employee_list)
This function modifies the employee list of dictionaries into a list of employee-department strings.

Parameters:

employee_list: A list of employee dictionaries.
Returns:

list: A list of strings consisting of employee names and departments.
generate_usernames(mod_list)
This function generates a list of usernames based on the employee-department strings.

Parameters:

mod_list: A list of employee-department strings.
Returns:

list: A list of usernames consisting of name + department delimited by underscores.
map_id_to_initial(employee_list)
This function maps each employee's ID to their first initial.

Parameters:

employee_list: A list of employee dictionaries.
Returns:

dict: A dictionary mapping an employee's ID to their first initial.
