trigger CatTrigger on Cat__c (after insert, after update, after delete) {
    
		if (Trigger.isAfter && Trigger.isInsert) {
			CatTriggerHandler.afterInsert(Trigger.new); 
    	}
		if (Trigger.isAfter && Trigger.isUpdate) {
			CatTriggerHandler.afterUpdate(Trigger.new);
    	}
		if (Trigger.isAfter && Trigger.isDelete) {
			CatTriggerHandler.afterDelete(Trigger.old);
    	}
}
