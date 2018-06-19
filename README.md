# hello-world
Hola Mundo
I created a live inventory in SQL for our warehouses.  I took us from a physical "P-Card" inventory system to an excel inventory that was updated each month.  Before I left the company, I completed a project to migrate our 1,000+ item inventory from Excel to SQL that sent out monthly reporting to the president and sales team via crontabs.  

The problem was manually notifying our sales team of updated item quantities, locations and discounting old stock. I solved this by implementing a mySQL live inventory database.  I configured it to send out monthly reports using crontabs to update our sales team and company president with new inventory items, quantity changes, revenue, and items that had not moved in over one year (dead inventory discount).

This resulted in more on time orders, 15% increased revenue and prompt discounting and sales of dead inventory items that were sitting in warehouses for over a
