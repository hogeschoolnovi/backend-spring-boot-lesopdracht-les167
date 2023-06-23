# Opdracht
## "Controller Test"

1. Open oefenproject in IntelliJ
2. Bestudeer de code in _OrderControllerTest.java_
3. Voeg unit test _‘shouldCalculateCorrectOrderAmount()’_ toe in __OrderControllerUnitTest__ die de JSON output van de _OrderController.getAmount()_ call controleert.
4. Run controller unit tests
5. Extra:
   - Voeg integrationtest _‘shouldReturnCorrectOrder()’_ toe in __OrderControllerIntegrationTest__ die de JSON output van de _OrderController.retrieveOrder_() call controleert (doe eerst POST en gebruik MvcResult en andReturn() om nieuwe ID uit response body te halen. Doe dan GET met deze ID).
6. Run controller integration tests