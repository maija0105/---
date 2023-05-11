# CascadingAuthenticationState>
<Router	AppAssembly="@typeof(Program).Assembly" PreferExactMatches="@true">
<Found Context="routeData">
<AuthorizeRouteView	RouteData="@routeData" DefaultLayout="@typeof(MainLayout)">
<NotAuthorized>
@if (!context.User.Identity.IsAuthenticated)
{
<RedirectToLogin />
}
else
{
 


resource.</p>
 
<p>You	are	not	authorized	to	access	this


}
 
</NotAuthorized>
</AuthorizeRouteView>
</Found>
<NotFound>
<LayoutView Layout="@typeof(MainLayout)">
<p>Sorry, there's nothing at this address.</p>
</LayoutView>
</NotFound>
</Router>
</CascadingAuthenticationState>
---
