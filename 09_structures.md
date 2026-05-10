A structure is a function that is always made first and put at the bottom of a program.
A structure is normally used to store information for later recall in the program.
An example of how it look and work:
Student GetStudentInfo()
{
    Student aStudent;
    C.WL("Please enter studenbt Id: ");
    aStudent.Id = C.TI64(C.RL());
    C.WL("Please enter the student name: ");
    aStudent.Name = C.RL();
    C.WL("Please enter the studen GPA: ");
    aStudent.GPA = C.TS(C.RL());
    return aStudent;
}

// The information lying

void DisplayStudentInfo(Student aStudent) // Student aStudent = s2;
{
    C.WL(aStudent.Id);
    C.WL(aStudent.Name);
    C.WL(aStudent.GPA);
}

struct Student
{
    public long Id; // PascalCase notation
    public string Name;
    public float GPA;
}
The reason why there's 'public' before the datatype is so that the information can be accesed when it's called, otherwise if you put 'private', it can't be accesed at all.
