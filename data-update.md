from members.models import Member
x = Member.objects.all()[4]
x.firstname 
x.firstname = "Stalikken"
x.save() 
Member.objects.all().values() 
