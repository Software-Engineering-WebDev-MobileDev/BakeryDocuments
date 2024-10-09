# Epic: Recipe Management
## Feature: Add new recipes
* **User story:** As an owner, I want to be able to add new recipes to the system.
* **Acceptance criteria:** The owner should be able to enter the recipe name, instructions, ingredients, and scaling factor.
*  **Estimated Time: Large (4 hour)**
## Feature: Edit existing recipes
* **User story:** As an owner, I want to be able to edit existing recipes.
* **Acceptance criteria:** The owner should be able to modify the recipe name, instructions, ingredients, and scaling factor.
*  **Estimated Time: Medium (2 hour)**
## Feature: Delete recipes
* **User story:** As an owner, I want to be able to delete recipes from the system.
* **Acceptance criteria:** The system should confirm the deletion and remove the recipe from all related data.
*  **Estimated Time: Small (2 hour)**
## Feature: View recipe details
* **User story:** As an employee, I want to view detailed information about a recipe, including ingredients, instructions, and scaling factor.
* **Acceptance criteria:** The employee should be able to see the recipe's name, instructions, a list of ingredients with quantities, and the scaling factor.
*  **Estimated Time: Small (1 hour)**
## Feature: Search for recipes
* **User story:** As an owner or employee, I want to be able to search for recipes by name or keyword.
* **Acceptance criteria:** The search results should be relevant and easy to navigate.
* **Estimated Time: Small (1 hour)**
# Epic: Ingredient Management
## Feature: Add new ingredients
* **User story:** As an owner, I want to be able to add new ingredients to the system.
* **Acceptance criteria:** The owner should be able to enter the ingredient name, quantity, and unit of measurement.
* **Estimated Time: Large (4 hour)**
## Feature: Edit existing ingredients
* **User story:** As an owner, I want to be able to edit existing ingredients.
* **Acceptance criteria:** The owner should be able to modify the ingredient name, quantity, and unit of measurement.
* **Estimated Time: Medium (2 hour)**
## Feature: Delete ingredients
* **User story:** As an owner, I want to be able to delete ingredients from the system.
* **Acceptance criteria:** The system should confirm the deletion and remove the ingredient from all related data.
* **Estimated Time: Medium (2 hour)**
## Feature: Track ingredient inventory
* **User story:** As an owner, I want to track the current inventory levels of ingredients.
* **Acceptance criteria:** The system should display the quantity of each ingredient available.
* **Estimated Time: Large (4 hour)**
## Feature: Receive low inventory alerts
* **User story:** As an owner, I want to be notified when the inventory of an ingredient falls below a certain threshold.
* **Acceptance criteria:** The system should send alerts to the owner when the inventory of an ingredient is low.
* **Estimated Time: Large (4 hour)**
# Epic: Task Management
## Feature: Create new tasks
* **User story:** As an owner, I want to be able to create new tasks for employees.
* **Acceptance criteria:** The owner should be able to enter the task description, assign it to an employee, and specify the shift.
* **Estimated Time: Large (4 hour)**
## Feature: Assign tasks to employees
* **User story:** As an owner, I want to be able to assign tasks to specific employees.
* **Acceptance criteria:** The owner should be able to select an employee and assign them to a task.
* **Estimated Time: Large (4 hour)**
## Feature: View task status
* **User story:** As an owner, I want to be able to view the status of tasks assigned to employees.
* **Acceptance criteria:** The system should display the task status (e.g., pending, in progress, completed).
* **Estimated Time: Medium (2 hour)**
## Feature: Mark tasks as completed
* **User story:** As an employee, I want to be able to mark tasks as completed.
* **Acceptance criteria:** The employee should be able to update the task status to "completed".
* **Estimated Time: Medium (2 hour)**
# Epic: Employee Management
## Feature: Create new employee accounts
* **User story:** As an owner, I want to be able to create new employee accounts.
* **Acceptance criteria:** The owner should be able to enter the employee's name, username, and password.
* **Estimated Time: Large (4 hour)**
## Feature: Edit existing employee accounts
* **User story:** As an owner, I want to be able to edit existing employee accounts.
* **Acceptance criteria:** The owner should be able to modify the employee's name, username, and password.
* **Estimated Time: Large (4 hour)**
## Feature: Delete employee accounts
* **User story:** As an owner, I want to be able to delete employee accounts.
* **Acceptance criteria:** The system should confirm the deletion and remove the employee from all related data.
* **Estimated Time: Medium (2 hour)**
# Epic: Mobile App
## Feature: Login and authentication
* **User story:** As a mobile app user, I want to be able to log in to the system using my credentials.
* **Acceptance criteria:** The mobile app should verify the user's credentials and provide access to the appropriate features.
* **Estimated Time: Large (4 hour)**
## Feature: View task list
* **User story:** As a mobile app user, I want to be able to view the list of tasks assigned to me for my current shift.
* **Acceptance criteria:** The mobile app should display the task list, including task descriptions and statuses.
* **Estimated Time: Large (4 hour)**
## Feature: Claim and complete tasks
* **User story:** As a mobile app user, I want to be able to claim and complete tasks assigned to me.
* **Acceptance criteria:** The mobile app should allow the user to claim tasks and update their status to "completed".
* **Estimated Time: Medium (2 hour)**
## Feature: View recipe details
* **User story:** As a mobile app user, I want to be able to view detailed information about recipes, including ingredients and instructions.
* **Acceptance criteria:** The mobile app should display the recipe's name, instructions, and a list of ingredients with quantities.
* **Estimated Time: Medium (2 hour)**
# Epic: Web App
## Feature: User login and authentication
* **User story:** As a web app user, I want to be able to log in to the system using my credentials.
* **Acceptance criteria:**
The login page should display a username and password field.
The system should validate the entered credentials against the database.
Upon successful login, the user should be redirected to the dashboard.
The system should handle failed login attempts with appropriate error messages.
## Feature: Dashboard overview
* **User story:** As a web app user, I want to see a dashboard that provides a summary of my tasks, inventory levels, and recent activity.
* **Acceptance criteria:**
The dashboard should display key metrics such as the number of pending tasks, low inventory items, and recent recipe additions.
The dashboard should provide visual representations of data (e.g., charts, graphs) to facilitate understanding.
The dashboard should be customizable to allow users to prioritize different metrics.
## Feature: Recipe management (web-specific)
* **User story:** As a web app user, I want to be able to search for and view recipe details in a more detailed format.
* **Acceptance criteria:**
The web app should provide a search bar to allow users to search for recipes by name or keyword.
Search results should be displayed in a clear and concise format, including recipe name, summary, and key ingredients.
Users should be able to click on a recipe to view its detailed instructions and ingredient list.
## Feature: Task management (web-specific)
* **User story:** As a web app user, I want to be able to view and manage tasks in a more comprehensive way, including filtering, sorting, and assigning tasks.
* **Acceptance criteria:**
The web app should provide filters to allow users to view tasks by status, assignee, or due date.
Tasks should be sortable by various criteria, such as due date, priority, or assignee.
Users should be able to assign tasks to themselves or other employees.
The web app should allow users to add comments to tasks and track their progress.
## Feature: Inventory management (web-specific)
* **User story:** As a web app user, I want to be able to view and manage inventory levels in detail, including setting reorder points and tracking stock movements.
* **Acceptance criteria:**
The web app should display a list of all ingredients with their current quantities and units of measurement.
Users should be able to set reorder points for ingredients to trigger alerts when inventory levels fall below a certain threshold.
The web app should track stock movements (e.g., when ingredients are used or received) to maintain accurate inventory records.
Users should be able to view historical inventory data to identify trends and patterns.
