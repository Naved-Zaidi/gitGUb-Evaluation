trigger PopulateAccountShippingAddress on Account (before insert) {
    
    if( Trigger.isInsert && trigger.isBefore)
    {
        PopulateAccountShippingAddressHandler.updateAddress(Trigger.new);
        
    }
}