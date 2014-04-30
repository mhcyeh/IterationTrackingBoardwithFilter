Iteration Tracking Board with Query Filter
=====================================

Added a query filter to the settings in the Iteration Tracking Board

Some users in Rally were requesting a way to filter user stories by initiative. While this functionality is available on the Portfolio Hierarchy and Portfolio Kanban, it was not available on the Iteration Tracking Board as that is the application that we are using.

To filter user stories by initiative, using the following code segment in the query filter:

(Feature.Parent.FormattedID = "(initiative number)")

To filter user stories by feature, using the following code segment in the query filter:

(PortfolioItem.FormattedID = "(feature number)")
