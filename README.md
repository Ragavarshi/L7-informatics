# Ice Cream Parlor Cafe Application

## Description
This is a simple Python application for managing an ice cream parlor cafe. It uses SQLite to manage:
- Seasonal flavor offerings
- Ingredient inventory
- Customer flavor suggestions and allergy concerns

Users can maintain a cart of their favorite products, search and filter offerings, and add allergens if they don’t already exist.

## Running the Application in Google Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload the `ice_cream_parlor.py` script to your Colab environment.
3. Ensure the SQLite database file (`ice_cream_parlor.db`) is also uploaded if you have existing data.
4. Open a new notebook and add the following code to run the script:

    ```python
    !python ice_cream_parlor.py
    ```

5. Follow the on-screen instructions to interact with the application.

## Database Initialization
The database and necessary tables are automatically created when you first run the application.

## Functionality
- **Add Flavor**: Add a new ice cream flavor to the database.
- **Add Ingredient**: Add a new ingredient to the database.
- **Add Customer Suggestion**: Record a customer suggestion.
- **Add Allergen**: Add a new allergen to the database.
- **Create Cart**: Create a new shopping cart for a customer.
- **Add to Cart**: Add a flavor to a customer's cart.
- **Search Flavors**: Search for flavors by name.
- **Filter Flavors**: Filter flavors based on seasonality.
- **View Cart**: View items in a customer's cart.

## Examples
### Adding a Flavor
1. Select option `1` from the main menu.
2. Enter the flavor name, description, and whether it's seasonal.

### Creating a Cart
1. Select option `5` from the main menu.
2. Enter the customer name.
3. The application will display the cart ID for future reference.

## Contributing
1. Fork the repository on GitHub.
2. Create a new branch: `git checkout -b feature-branch`.
3. Make your changes and commit them: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-branch`.
5. Open a pull request on GitHub.

## License
This project is not licensed.

## Contact Information

For support or inquiries, please contact [ragavarshinis1025@gmail.com](mailto:ragavarshinis1025@gmail.com).
