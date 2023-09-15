# Frontend Developer Assignment_Totality Corp
Deployed Link- https://650467690b3a452d8a7747ce--capable-mandazi-17cb59.netlify.app/
    First use the comment (npm install)
    then (npm start) to run in your production environment

    - Install react (npx install create-react-app)
    - Install tailwind css for making interactive user interface (
        postcss is a tool for transforming css with javascript
        tailwind css use without ever leaving your html it is a utility first css framework

        npm install -D tailwindcss postcss
        npx tailwindcss init

        @tailwind base;
        @tailwind components;
        @tailwind utilities;
    )
    - Install redux for creating and managing store(
        # Redux ToolKit
            - Install @reactjs/toolkit & react-redux
            - Build our store
            - Connect our store to our app
            - Slice (orebiSlice.js)
            - Dispatch the action
            - Selector (Read the data)
    )
    - Install Framer Motion for creating amazing animations and interaction in Framer(
        Install framer-motion with via your package manager:
        npm install framer-motion

        Then import the motion component:
        import { motion } from "framer-motion"
        export const MyComponent = ({ isVisible }) => (
        <motion.div animate={{ opacity: isVisible ? 1 : 0 }} />
)
    )
    - Install react-icons for using icons in our project(
        Installation - npm install react-icons --save
    
        Example - 
        import { FaBeer } from "react-icons/fa";
        function Question() {
          return (
            <h3>
              Lets go for a <FaBeer />?
            </h3>
          );
        }
    )
    - Install react-paginate with npm directly for the pagination functionality of any list(
        npm install react-paginate --save
    )
    - Install react-redux(
        npm install react-redux
    )
    - Install react-router-dom contains binding for using React Router in web application from this we route from one component to another(
        npm i react-router-dom
    )
    - Install react slick for carousel built with react(
        npm install react-slick --save
    )
    - Install react persist use to seamlessly save the application redux state object to async storage(
        npm install redux-persist
    )
