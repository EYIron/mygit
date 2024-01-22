Confirm Records Returned

//Query Return Confirm

var myObj = new GlideRecord('incidnet');
myObj.addQuery('caller_id',current.caller_id);
myObj.query();
var retRows = myobj.getRowCount();
gs.info("Returned numner of rows = " + retRows) ;

// getRowCount()-less code,nut larger performance impact
GlideAggregate()-more code, but executes faster   //

var count = new GlideAggregate('incident') ;
count.addQuery('caller_id',current.caller_id) ;
count.addAggregate('COUNT');
count.query();
var incidents = 0 ;
if (count.next()) {
incidents = count.getAggregate('COUNT') ;
}
gs.info("Returned number of rows = " + incdients) ;


