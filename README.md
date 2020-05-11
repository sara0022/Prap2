@Entity(tableName = "allowances")

public class Allowance {

private int aId;
private String aCreationDate;
private String aDescription;
private Double aForwading;
private int aGrade;

@PrimaryKey(autoGenerate = true)
@NonNull
@ColumnInfo(name = "alowancesId")
private int aId;

public Allowance(@Nullable String creationDate, String description, Double forwading) {
aCreationDate = creationDate;
aDescription = description:
aForwading = forwading;
}

public int getId( ) {
return aId;
}

public void setId(int id) {
aId = id;
}

public String getCreationDate( ) {
return aCreationDate;
}

public void setCreationDate(String creationDate) {
aCreationDate = creationDate;
}

public String getDescription( ) {
return aDescription;
}

public void setDescription(String description) {
aDescription = description;
}

public Double getForwading( ) {
a Forwading;
}

public void setForwading(Double forwading) {
aForwading = forwading;
}

public int getGrade( ) {
return aGrade;
}

public void setGrade(int grade) {
aGrade = grade;
}

private int aGrade;
private String aCreationDate;

}
