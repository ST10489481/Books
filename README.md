# link:#
https://github.com/ST10489481/Books.git

# Main screen
<img width="848" height="923" alt="Screenshot 2026-02-02 131020" src="https://github.com/user-attachments/assets/5cce1f24-cba0-45f6-90cb-1cca169191c3" />
<img width="745" height="535" alt="Screenshot 2026-02-02 131058" src="https://github.com/user-attachments/assets/aad3735b-efe9-4f0f-9c55-ad262b7eaa06" />

# Detailed screen
<img width="697" height="879" alt="Screenshot 2026-02-02 132417" src="https://github.com/user-attachments/assets/f404f21a-7d71-43e6-bc34-afc166d0fe09" />
<img width="795" height="821" alt="Screenshot 2026-02-02 132444" src="https://github.com/user-attachments/assets/50e72a67-159c-4cce-ba1c-c6cc32428919" />

# Explamation of app

## Main Screen
Book Review Button   
Collects the entered details and creates a book object 

Detailed Button 
Navigates to DetailedActivity to view stored reviews and calculations.

Exit Button  
Calls finishAffinity() to close the app completely.

## Detailed screen 

TextView ListView - Displays all stored books.

TextView calculateView -Shows average rating.

Button: Return Return to the main screen

List Button  
Observes bookViewModel.allBooks and displays all book details in a formatted list.

Calculate Button 
Observes bookViewModel.Books and calculates the average rating of all books.

Return Button   
Navigates back to MainActivity.

