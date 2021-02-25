<!-- @format -->

# django-to-do-list

todo list created in django

# Setup

> 1. Make sure you have Django and Python installed
> 2. CD into todo
> 3. Run the following command
>    > python manage.py runserver
> 4. Live Environment can be found here at [http://127.0.0.1:8000/](http://127.0.0.1:8000)
> 5. Proceed with Create, Read, Update, and Delete (CRUD)
> 6. Once finished, run the following command:
>    > > Quit the server with CTRL+BREAK (CTRL+C)

# Tips

## Changing the port

> By default, the runserver command starts the development server on the internal IP at port 8000.
>
> > If you want to change the server’s port, pass it as a command-line argument. For instance, this command starts the server on port 8080:
> >
> > > python manage.py runserver 8080

> > If you want to change the server’s IP, pass it along with the port. For example, to listen on all available public IPs (which is useful if you are running Vagrant or want to show off your work on other computers on the network), use:
> >
> > > python manage.py runserver 0:8000

> > 0 is a shortcut for 0.0.0.0.
