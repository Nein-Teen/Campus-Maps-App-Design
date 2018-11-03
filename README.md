
# Campus Maps

## 1. User Stories (Required and Optional)

**Required Must-have Stories**

 * User can enter the building and room number into a search bar and a path will be shown to it starting from their current location (along with the time estimate for them to get there).
 * User can login, which will slightly tweak the destination process based on preferences, previous behavior

**Optional Nice-to-have Stories**

 * 3D Map
 * Autocomplete when typing searches that have been already typed before (recents, favorites, etc.)
 * Alarms/Reminders for saved locations: latest time for reminder would be the commute time to classroom 

## 2. Screen Archetypes

 * Login Page
   * User will be able to log in or click on "Sign up" to create an account.
 * Registration Screen
     * User is required to input name, email, password, and university
 * Input Destination Screen
   * User will be able to input starting point and input ending point, both will be used as geolocation may not work perfectly with many students on campus using the same wi-fi source
   * User will also be able to put in any preferences for their route (highways/tollgates) to filter out some paths
 * Map Screen
   * User will be provided with the path from current location to destination, along with estimated time of commute
 * Favorites Screen
     * User will be able to save favorite/frequent locations 
     * User will be given the option of setting reminders/alarms for saved locations so they can get a reminder to start for class according to the time it'll take them to get there from their current location.

## 3. Navigation

**Tab Navigation** (Tab to Screen)

 * Favorites Screen
 * Input Destination Screen
 * Map Screen

**Flow Navigation** (Screen to Screen)

 * Login Screen
   * Login Button -> Home Page (Map)
   * Sign up Button -> Registration Screen
 * Registration Screen
    * Make Account Button -> Home Page(Map) 
 * Map Screen
   * Search/Text Bar-> Input Destination Screen
 * Favorites Screen
     * Selecting one destination -> Map Screen with destination filled in
 * Input Destination Screen
     * Favorites Button -> Favorites Screen
     * Navigate Button -> Map
