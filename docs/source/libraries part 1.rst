authentication library

  Classes

    GoogleSignInButton
    
    Creates a simple button to allow the user to sign in with Google. If the user is signed in, the button instead displays text stating the user's email address.
  
authenticator library

  Functions

    getClientId() → String
    
    Returns the OAuth 2.0 Client ID to be used for Google authentication.
  
    getScopes() → List<String>
    
    Returns the access scopes to be used for Google authentication.

building library

  Classes
  
    Building
    
    Holds information about the building types. This object is to be used when fetching information from the database.

building_manager library

  Classes

    BuildingManager

    This object will allow the main application to interface with the rest of the objects in the 'Building Manager' sub system.

buildinginfo library

  Classes

    BuildingInfo
    
    A widget that displays the information for a specified Building.
    
    CurrentBuildingInfo
    
    Holds the current Building (if there is one), that the user wishes to view the information for.

database library

  Classes

    Database

    Describes a local database used to store various information pertraining to buildings, bus routes, favourites, etc.
