# Library Book Checkout Simulation and Optimization
This project simulates a county library system managing two categories of books: standard books and new arrivals. It models the checkout and return process across multiple library branches, aiming to optimize the availability of books for patrons.

## Project Overview
### Context:
New arrivals have higher demand and shorter checkout periods (2 weeks) compared to standard books (3 weeks). After six months, new arrivals are reclassified as standard books.

### System Mechanics:

Patrons request books online from any branch.

Books are transported to the patron’s selected branch for pickup.

Books can be checked out, returned, become overdue, or be deemed lost if not returned after a grace period.

Returned books are shelved and made available again.

### Goal:
Maximize the percentage of books that are either available on shelves or currently checked out, excluding overdue or lost books.

## Key Insights
Longer checkout times generally increase the percentage of books available or in use.

A contour plot and a 3D response surface show that the highest availability corresponds to the longest checkout times for both book categories.

However, maximizing checkout times can create a bottleneck of requests, causing waitlists and potential dissatisfaction among patrons.

Examining the ratio of standard to new book checkout times reveals that:

Maximum availability occurs when checkout times are roughly equal (1:1 ratio).

If new books have longer checkout times than standard books (eta > theta), overall availability tends to be higher.

This suggests that extending checkout periods for new arrivals impacts availability more significantly.

## Model Limitations & Future Work
The current model does not include renewals, which in real-world libraries allow standard books to be renewed a limited number of times.

Adding a ‘renewed’ state for standard books, tracking renewal counts, and enforcing renewal limits would enhance realism and improve decision-making.
