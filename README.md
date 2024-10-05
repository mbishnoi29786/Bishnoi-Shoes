# Bishnoi Shoes

## Overview

**Bishnoi Shoes** is an online shoe store that offers two separate portals: one for users and one for the admin. Users can browse products, while the admin can manage inventory, view transactions, and oversee customer interactions.

### Access Links

- **Admin Portal**: [http://localhost/bishnoi_shoes/admin/admin_home.php](http://localhost/bishnoi_shoes/admin/admin_home.php)
- **User Portal**: [http://localhost/bishnoi_shoes/index.php](http://localhost/bishnoi_shoes/index.php)
  - After logging in: [http://localhost/bishnoi_shoes/home.php](http://localhost/bishnoi_shoes/home.php)

## Features

### Admin Portal

- **Dashboard**: View graphs of all product shares by brand according to the year using libraries like Chart.js, Highcharts.js, and exporting.js.
- **Product Management**: Adjust which products are featured and categorized under new arrivals (Basketball, Football, Running).
- **Transaction Management**: View order details, change transaction statuses, and cancel user orders.
- **Customer Management**: See all customers and their details.
- **Message Management**: View messages left by customers regarding stock requests or reviews.
- **Order Management**: Review all orders approved by the admin.

### User Portal

- **Browse Products**: Users can see all products, but need to log in or register to add items to the cart.
- **Home Page**: Featured products are displayed for easy access.
- **Product Categories**: Products are organized by category for user convenience.
- **Contact Us**: Users can reach out to the admin or store owner.
- **Product Details**: After selecting a product, users can view detailed information and add it to their cart.
- **Cart Management**: Users can view all items in their cart, adjust quantities, and remove products before purchasing.
- **Order Summary**: After placing an order, users are directed to an order summary page confirming the successful placement of their order.

### Order Information

Currently, the order functionality is limited to **Cash on Delivery**.

## Setup Instructions

1. **Clone the repository** (once it's on GitHub):
   ```bash
   git clone https://github.com/mbishnoi29786/Bishnoi-Shoes.git
   ```

2. **Move Project Files**: Copy the project files to the `htdocs` directory of your XAMPP installation.

3. **Run the XAMPP Server**: Start the XAMPP Control Panel and run the Apache and MySQL modules.

4. **Access the Application**: Open your web browser and navigate to [http://localhost/bishnoi_shoes](http://localhost/bishnoi_shoes).

## Note

Some JavaScript libraries (Chart.js, Highcharts.js, and exporting.js) are available online and should be downloaded separately for full functionality. As such, they are not included in this repository.

You can see the screenshots of the **Admin Portal** and **User Portal** in the directories `admin screenshots` and `user screenshots`.

If you need any help setting up this project, feel free to email me at `mbishnoi29786@gmail.com`.


## Contributing

Contributions to the project are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
