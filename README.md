# keycloakTest
Test Project for Keycloak
Keycloak Setup ----
1. Install keycloak
2. Setup Admin Account
3. Add realm with name "SpringBootSecurity"
4. Now in this realm add a client named "SpringBootSecured"
5. Add role named "user"
6. Create an user with username and password in keycloak

Java Setup -------
1. Clone this repository
2. check application.properties and cross verify the details with your keycloak configs
3. run the spring boot app using command "**mvn spring-boot:run**"
4. Open you browser and hit "http://localhost:8081/test"
5. If all the configurations are ok you will see a keycloak login page.
6. Enter the credentials of the user that you just created in the keycloak.

**Done**
