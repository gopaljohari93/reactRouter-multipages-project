		  
	Ye important nahi aap ko yaad kya rah raha hai & ye important hai isko vapis search kaise karna hai
	
	1)a tag use nahi karte ku ki page refresh hota hai isliye Link tag use karte hai
	2)Navlink additional chije provide karta hai 
	
	 summary 1)outlet in layout se nesting ki ja sakti hai
			 2)main.jsx me layoutdiya top level par
			 3)router kaise banate hai ek provider chahiye
			 4)createBrowserRouter se hi router banega
			 5)dynamic value kaise le userid
			 6)api call loader
			 
	1)react install vite 
	2)tailwind css install
	3)reactrouter install
	4)npm run dev
	5)create components
	6)create Header html jsx and import Link, Navlink header
	7)Navlink isactive set header
	8)create Footer html jsx and import Link
	9)create Home html jsx 
	10)main.jsx reactrouter website - router kaise banate hai
	11)header footer same rahe ander ke component change hote rahe- new file create Layout.jsx
	12)Layout.jsx import components Header footer  
	13)dynamically Header footer import use Outlet main.jsx
	14)main.jsx  <Route path='/' element={<Layout />}>
	15)Header.jsx Link Home copy and paste About - to="/" to="/about" to="/contact" 
	16)User.jsx html
	17)path create main.jsx - <Route path='user/:userid' element={<User />} />
	18)User.jsx import useParams 'react-router-dom'
	19)Github.jsx style taliwind css Github followers
	20)Api call useEffect - fetch('https://api.github.com/users/name'), useState
	21)loader - use hook userloaderdata