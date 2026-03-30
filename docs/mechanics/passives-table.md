# Passives

=== "Fighter Skills" {{ populate_quicklist(file='skills.csv',return_columns=['Name','Type','Level'],filter_column='Class',filter_values=['Fighter']) | linkify_quicklist_skillnames | convert_to_md_table | add_indentation(spaces=4) }}

=== "Fighter"
    {{ populate_quicklist(file='passives-table.csv',return_columns=['Passive Name','Level','Inherit','Potential','L1','L2','L3','L4','L5','L6','L7'],filter_column='Class',filter_values=['Fighter']) | linkify_quicklist_skillnames | convert_to_md_table | add_indentation(spaces=4) }}









