## Description
 Adds a new product category page to the MSChoose website, enabling users to view curated collections for specific occasions, such as formal events, casual outings, and seasonal trends.

<hr/>

```bash
// IMPORTANT | IMPORTANT | WARNING | CAUTION
```

> [!IMPORTANT] 
> Ensure all links on the new page are functional, and that product images load quickly, even on mobile devices.

<hr/>

## Checklist
- [x] Created a category page layout with responsive design.
- [x] Integrated the API for dynamically loading product data.
- [x] Updated the navigation menu to include the new category link.
- [x] Ensured SEO-friendly URLs for new category pages.

<hr/>

## Tests
- Verified product images and details load correctly on different screen sizes.
- Tested links for navigation and cart functions across categories.
- Confirmed that SEO metadata updates dynamically with each category.

<hr/>

## Run
### Step-by-Step Guide to Run the Project Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/mschoose/www.mschoose.com.git
   ```


2. **Navigate to the Project Directory**
   ```bash
    cd www.mschoose.com
   ```


3. **Install Dependencies**
- Ensure you have Node.js and npm installed.
- Run the following command to install the required packages:
   ```bash
    npm install 
    // or
    pnpm install 
   ```


4. **Set Up Environment Variables**
- Duplicate the `.env.example` file and rename it to `.env`.
- Fill in the necessary environment variables such as `API_URL` and `DATABASE_URL`.
   ```bash
    cd www.mschoose.com
   ```

5. **Run the Development Server**
- Start the local development server with.
   ```bash
    npm run dev
   ```
- The application should now be accessible at `http://localhost:3000`.


6. **Build for Production (Optional)**
- To build the project for production, use.
   ```bash
  npm run build
   ```

7. **Start the Production Server (Optional)**
- After building, you can start the production server with:
   ```bash
  npm start
   ```