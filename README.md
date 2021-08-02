# email_j2EE
TOMCAT - 10
Servlet API - jakarta


Listeners :
1. ApplicationContextListener - is a ServletContextListener, whose function will run at the time of deployment before any request.
                                DB connection object is created and saved to ServletContext, which can be shared all over the application

Filters :
1. AuthenticateFilter - it interprets all the secured urls (or Servlets) request, validate if user is authenticated or not.

Servlets : 
1. HelloServlet
2. RegisterServlet
3. LoginServlet
4. ComposeServlet
5. DraftServlet
6. InboxServlet
7. SentServlet
8. WelcomeServlet
9. LogoutServlet
