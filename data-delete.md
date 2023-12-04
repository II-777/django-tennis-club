from members.models import Member
x = Member.objects.all()[5]
x.firstname 
x.delete() 
Member.objects.all().values() 