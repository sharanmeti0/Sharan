using System;
using System.Collections.Generic;
using System.Linq;
using System.Threading.Tasks;

namespace WebApplication1.Controllers
{
    public class EmplyeedetailsController : Controller
    {
        private string FirstName;
        private string LastName;

 

        public ActionResult Index()
        {
            EmplyeedetailsController emp = new EmplyeedetailsController
            {
                FirstName = "Raj",
                LastName = "Guru"
            };
            ViweBag.message = emp;
            return View();
        }
    }
}
