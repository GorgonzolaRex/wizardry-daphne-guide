# Passives

- WIP
- Intro text here
- Scope
- Missing data, reporting
- 

### Nameless

| Name          | Stat     | L1 | L2 | L3 | L4  | L5  | L6  | L7  | L8  | L9  | L10 | L11 | L12 | L13 | L14 |
| :------------ | :------- | -- | -- | -- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Dwarf         | HP       | +4 | +6 | +8 | +10 | +14 | +16 | +18 | +20 | +22 | +28 | +30 | +32 | +36 | +40 |
| Human Priest  | MP       | +2 | +3 | +4 | +5  | +7  | +8  | +9  | +10 | +11 | +14 | +15 | +16 | +18 | +20 |
| Human Fighter | ATK      | +2 | +3 | +4 | +5  | +7  | +8  | +9  | +10 | +11 | +14 | +15 | +16 | +18 | +20 |
| Elf Mage      | MAG      | +2 | +3 | +4 | +5  | +7  | +8  | +9  | +10 | +11 | +14 | +15 | +16 | +18 | +20 |
| Elf Priest    | DIV      | +2 | +3 | +4 | +5  | +7  | +8  | +9  | +10 | +11 | +14 | +15 | +16 | +18 | +20 |
| Beast Thief   | ACC      | +2 | +3 | +4 | +5  | +7  | +9  | +9  | +10 | +11 | +14 | +15 | +16 | +18 | +20 |
| Human Ninja   | ASPD     | +1 | +2 | +3 | +4  | +5  | +6  | +7  | +8  | +9  | +10 | +11 | +12 | +13 | +14 |
| Human Samurai | ATK, MAG | +1 | +2 | +3 | +4  | +5  |     |     |     |     |     |     |     |     |     |

### Class 

=== "Fighter"
    {{ populate_quicklist(file='passives-table.csv',return_columns=['Passive Name','Level','Inherit','Potential','L1','L2','L3','L4','L5','L6','L7'],filter_column='Class',filter_values=['Fighter']) | linkify_quicklist_skillnames | convert_to_md_table | add_indentation(spaces=4) }}

=== "Knight"
    {{ populate_quicklist(file='passives-table.csv',return_columns=['Passive Name','Level','Inherit','Potential','L1','L2','L3','L4','L5','L6','L7'],filter_column='Class',filter_values=['Knight']) | linkify_quicklist_skillnames | convert_to_md_table | add_indentation(spaces=4) }}

=== "Thief"
    {{ populate_quicklist(file='passives-table.csv',return_columns=['Passive Name','Level','Inherit','Potential','L1','L2','L3','L4','L5','L6','L7'],filter_column='Class',filter_values=['Thief']) | linkify_quicklist_skillnames | convert_to_md_table | add_indentation(spaces=4) }}

=== "Priest"
    {{ populate_quicklist(file='passives-table.csv',return_columns=['Passive Name','Level','Inherit','Potential','L1','L2','L3','L4','L5','L6','L7'],filter_column='Class',filter_values=['Priest']) | linkify_quicklist_skillnames | convert_to_md_table | add_indentation(spaces=4) }}

=== "Mage"
    {{ populate_quicklist(file='passives-table.csv',return_columns=['Passive Name','Level','Inherit','Potential','L1','L2','L3','L4','L5','L6','L7'],filter_column='Class',filter_values=['Mage']) | linkify_quicklist_skillnames | convert_to_md_table | add_indentation(spaces=4) }}

=== "Ninja"
    {{ populate_quicklist(file='passives-table.csv',return_columns=['Passive Name','Level','Inherit','Potential','L1','L2','L3','L4','L5','L6','L7'],filter_column='Class',filter_values=['Ninja']) | linkify_quicklist_skillnames | convert_to_md_table | add_indentation(spaces=4) }}

=== "Samurai"
    {{ populate_quicklist(file='passives-table.csv',return_columns=['Passive Name','Level','Inherit','Potential','L1','L2','L3','L4','L5','L6','L7'],filter_column='Class',filter_values=['Samurai']) | linkify_quicklist_skillnames | convert_to_md_table | add_indentation(spaces=4) }}

=== "Ranger"
    {{ populate_quicklist(file='Passives-table.csv',return_columns=['Passive Name','Level','Inherit','Potential','L1','L2','L3','L4','L5','L6','L7'],filter_column='Class',filter_values=['Ranger']) | linkify_quicklist_skillnames | convert_to_md_table | add_indentation(spaces=4) }}







