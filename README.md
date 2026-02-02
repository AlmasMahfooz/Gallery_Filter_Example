# Gallery_Filter_Example


Table : Dataverse

Gallery Items Property.

Filter(

    'Favourite Books',
    
             TextInput3.Text in 'Book Name'  Or  IsBlank(TextInput3.Text),
             
             Rating=varStarRating  Or  Dropdown3.SelectedText.Value="All"   
             
)
