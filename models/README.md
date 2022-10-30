# AirBnB clone - Models
This directory contains all classes used to store information for the website.
## File Structure
- [base_model.py](base_model.py) - The BaseModel class from which future classes will be derived
- [amenity.py](amenity.py) - contains the Amenity class, derived from BaseModel
- [city.py](city.py) - contains the City class, derived from BaseModel
- [place.py](place.py) - contains the Place class, derived from BaseModel
- [review.py](review.py) - contains the Review class, derived from BaseModel
- [state.py](state.py) - contains the State class, derived from BaseModel
- [user.py](user.py) - contains the User class, derived from BaseModel
  - **[engine](engine)** directory contains all storage classes:
    - [file_storage.py](engine/file_storage.py) - serializes/deserializes instances to/from a JSON file
    - [db_storage.py](engine/db_storage.py) - saves and loads instances to/from a MySQL database
