<table width="100%" border="0" cellspacing="0" cellpadding="0">
     <tr>
 <td align="left" valign="top" style="padding: 0 0 0px 0"> 
 
    <table align="center" border="0" cellpadding="0" cellspacing="0" class="fixed-table-87" role="presentation" width="600">
  <tr>
    <td align="center"  style="font-family:Arial,Helvetica,sans-serif; color:#333333; text-align:left; font-size:16px; line-height:22px; margin:0; padding:20px 40px 0 40px;"  class="pad20" valign="top">
  %%=v(@FirstName)=%%
    </td>
    
    </tr>
    
    </table>
 
 %%[IF @VAR016=="0" THEN]%%
   %%=v(@body)=%%
   
   %%[ELSE]%%
      %%=v(@body)=%%
   %%[ENDIF]%%
</td>
    </tr>
</table>
