# aspire-app
It will help to keep track of all the loan information and help to faster proceed all the requests

validate cross browser **"https://aspireapp.odoo.com"** : which browser is supported & which browser is not supported .

validate log in : log in  by validuser id  by user Account: "user@aspireapp.com" Password: "@sp1r3app" .it will work .

once log in to portal validate overview page : after log in it should show overview page with 3 buttons "Discuss" ,"Inventory" ,"Manufacturing"

After log in portal navigate to Inventory : while click on Invetory page -it should redirect to onventory page .https://aspireapp.odoo.com/web#cids=1&action=232&model=stock.picking.type&view_type=kanban&menu_id=108

In inventory page :From the top-menu bar, select `Products -> Products` item, then create a new product ,click on create tab -one page will open -type product name "mayosauce" & in general info -give details .https://aspireapp.odoo.com/web#cids=1&menu_id=108&action=215&model=product.template&view_type=form

After create a new product update : Update the quantity of new product is more than 10 -update it .https://aspireapp.odoo.com/web#cids=1&menu_id=108&action=215&model=product.template&view_type=form

From top-left page, click on `Application` icon : again overview page of aspire will open .

Navigate to `Manufacturing` feature, then create a new Manufacturing Order item for the created Product for mayosauce .

Update the status of new Orders to “Done” successfully :once create order with same quantity https://aspireapp.odoo.com/web#menu_id=150&cids=1&action=285&model=mrp.production&view_type=list

Validate the new Manufacturing Order is created with corrected information:Manufacturing Orders/WH/MO/01418 :it can visible with detailed info & status under manufacturing orders https://aspireapp.odoo.com/web#menu_id=150&cids=1&action=285&model=mrp.production&view_type=list

If any error will show while doing steps : it should be tracked by log file or user monitoring in azure where admin users can track 

