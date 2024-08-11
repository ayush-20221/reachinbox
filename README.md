# ReachInBox-Frontend

## Overview
This repository contains the code for Reachinbox frontend  App using React with Typescript for an assignment given by Reachinbox.

## Technologies Used ( Frontend )
  - React
  - Typescript
  - Tailwind CSS

## Figma Design
https://www.figma.com/design/uECxqvFhEx9dn4ZuO7wqmu/Reachinbox-Assignment?node-id=0-1

## API Used  
https://documenter.getpostman.com/view/30630244/2sA2rCTMKr#f45cb7f3-d007-4df5-83f4-ea598d3e5015


## Demo Video :- 
https://www.loom.com/share/b12a1f9ab67e48ae8e90efff18bccc9b?sid=6a306c49-9d1a-4b37-9dfa-21b4538e3831



 # How to Run <br/>
 
   <h2>Installation</h2>
   
   Clone the repository:   ``` git clone https://github.com/JahirPendhari09/ReachInBox-Frontend.git  ``` <br/>
   Navigate to the project directory:   ``` cd reachinbox ``` <br/>
   Install the dependencies:   ``` npm install ``` <br/>
   Start the development server:   ``` npm run dev ``` <br/>
   Open your browser and visit:   ```  http://localhost:5173/ ``` <br/>
  

 
  

   ## Features 
   
  - Authentication
  - Get Emails
  - Post (send) Email
  - Delete Email


   <h2>Endpoints</h2>
   <h3>All Emails</h3>
   <pre><code>GET {https://hiring.reachinbox.xyz/api/v1//onebox/list} </code></pre>

   <h3>All Emails from Onebox</h3>
   <pre><code>GET {https://hiring.reachinbox.xyz/api/v1//onebox/messages/:thread_id} </code></pre>

   <h3>Add Onebox Mail</h3>
   <pre><code>POST {https://hiring.reachinbox.xyz/api/v1//onebox/reply/:thread_id} </code></pre>

   <h3>Delete Email</h3>
   <pre><code>DELETE {https://hiring.reachinbox.xyz/api/v1//onebox/messages/:thread_id} </code></pre>

 

  
  
