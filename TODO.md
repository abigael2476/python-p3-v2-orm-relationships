# TODO List for Implementing One-to-Many Relationship

- [ ] Update lib/employee.py:
  - [ ] Import Department class
  - [ ] Modify **init** to accept department_id parameter
  - [ ] Update **repr** to include department_id
  - [ ] Update create_table to add department_id column with foreign key
  - [ ] Update save method to include department_id
  - [ ] Update update method to include department_id
  - [ ] Update create classmethod to accept department_id
  - [ ] Update instance_from_db to handle department_id
- [ ] Update lib/department.py:
  - [ ] Add employees() method to return list of associated Employee instances
- [ ] Run pytest to verify implementation
