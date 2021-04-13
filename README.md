Steps to reproduce:

  1. npm install from root 
  -- notice that App1 version of date-fns (2.20.0) was hosited to root and App2 has date-fns install in its local node_mods (2.15.0)
  2. update App2 version of date-fns to match App1 version (2.20.0)
  3. npm install from root
  
  Notice - App2 still has the outdate package installed locally and will still resolve 2.15.0 and can not be updated without manual action
