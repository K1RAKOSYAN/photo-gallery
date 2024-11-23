# K44A's Photo Gallery 🎉  

A dynamic photo gallery application built with React and the Unsplash API. This project is perfect for exploring React concepts, API integrations, and custom theming using CSS variables.  

---

## **Features**  

- **React Components:** Organized and reusable components for better readability and scalability.  
- **API Integration:** Fetch random photos or search for photos based on user-defined queries using the Unsplash API.  
- **Dynamic Search:** Instantly load photos by keyword with a seamless search experience.  
- **Responsive Design:** Ensures the gallery looks stunning on devices of all sizes with CSS grid layouts.  
- **Custom Theming:** Easily tweak the application's appearance using CSS variables for a personalized touch.  

---

## **Technologies Used**  

- **React:** State management, hooks, props, and JSX for building interactive UI.  
- **JavaScript:** Utilized for functions, conditionals, loops, and the fetch API for data handling.  
- **CSS:** Implements variables, flexible layouts, and responsive design.  
- **Unsplash API:** Provides access to dynamic photo content for the gallery.  

---

## **Getting Started**  

---

### **Clone the Repository**  

-- **git clone** https://github.com/yourusername/k44a-photo-gallery.git  
cd k44a-photo-gallery  

---

## **Install Dependencies**
Make sure you have Node.js installed. Then, run the following command:

---

## **bash**
npm install  

## **Set Environment Variables**
Create a .env file in the project root directory and add the following:

## **plaintext**

REACT_APP_CLIENT_ID=your_unsplash_client_id  
REACT_APP_UTM=?utm_source=your_project_name  
REACT_APP_API_KEY=your_api_key  

## **Run the Development Server**
-- **Start the app locally:**

## **bash**

npm start  

- **Your application will now be running at http://localhost:3000.**

---

## **How to Use**  

1. Enter a search term in the input field (e.g., "nature", "cars").  
2. Click **Search** or press **Enter** to fetch related photos.  
3. Hover over any photo to see the photographer's credits and a link to Unsplash.  

---

## **Customizing the Project**  

### **Change the Theme**  
Modify the `:root` variables in `style.css` to:  
- Adjust the background image.  
- Change the primary color scheme.  
- Use a custom font for your theme.  

### **Add More Columns**  
Update the `column-count` property in the `.grid` CSS class to control the number of columns displayed.  

---

## **How to Contribute**  

1. Fork this repository.  
2. Submit a pull request with your enhancements.  
3. Report any issues or bugs via GitHub's issue tracker.  
4. Share your suggestions for new features—ideas are always welcome!  
