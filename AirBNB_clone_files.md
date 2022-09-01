## AirBnB_clone Files and Directories
| File | Description |
| ---------------------- | ---------------------- |
|models | Directory will contain all classes used for the entire project. A class, called “model” in a OOP project is the representation of an object/instance. |
|tests | Directory will contain all unit tests. |
|console.py | File is the entry point of our command interpreter. |
|models/base_model.py |File is the base class of all our models. It contains common elements: |
| | attributes: id, created_at and updated_at methods: save() and to_json() |
|models/engine | Directory will contain all storage classes (using the same prototype). For the moment you will have only one: file_storage.py. |

### BaseModel
Write a class BaseModel that defines all common attributes/methods for other classes:
| File | Description |
| ---------------------- | ---------------------- |
| `base_model.py`|  class BaseModel that defines all common attributes/methods for other classes:

- `models/base_model.py`
- create a file `base_model.py`
- 
