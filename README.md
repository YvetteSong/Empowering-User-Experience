# Empowering User Experience
Optimizing Product Recommendations through AB Testing and UI Enhancements

# Background #
We have data about users who enroll/visit a course page. We know the goal is to come uo with recommendations for the product and marketing teams to implement the changes or not. We have a new UI change and we want to investigate whether to launch the cahnge given the data below.

# Data #
Each row represents an interaction record of a user. The dataset includes the following columns:
user_id: A unique identifier for each user.
timestamp: The timestamp when the user visited the page.
group: The experimental group the user belongs to, including "control" (control group) and "treatment" (treatment group).
landing_page: The page the user saw, either "old_page" (old page) or "new_page" (new page).
converted: Whether the user converted (e.g., registered, made a purchase, etc.), with 1 indicating conversion and 0 indicating no conversion.
